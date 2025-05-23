---
id: autorender
title: Auto-render Extension
---
This is an extension to automatically render all of the math inside of text. It
searches all of the text nodes within a given element for the given delimiters,
ignoring certain tags like `<pre>`, and renders the math in place.

## Usage
This extension isn't part of KaTeX proper, so the script needs to be included
(via a `<script>` tag) in the page along with KaTeX itself.  For example,
using a CDN:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.22/dist/katex.min.css" integrity="sha384-5TcZemv2l/9On385z///+d7MSYlvIEw9FuZTIdZ14vJLqWphw7e7ZPuOiCHJcFCP" crossorigin="anonymous">
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.16.22/dist/katex.min.js" integrity="sha384-cMkvdD8LoxVzGF/RPUKAcvmm49FQ0oxwDF3BGKtDXcEc+T1b2N+teh/OJfpU0jr6" crossorigin="anonymous"></script>
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.16.22/dist/contrib/auto-render.min.js" integrity="sha384-hCXGrW6PitJEwbkoStFjeJxv+fSOOQKOPbJxSfM6G5sWZjAyWhXiTIIAmQqnlLlh" crossorigin="anonymous"
    onload="renderMathInElement(document.body);"></script>
```

> Above, the [`defer` attribute](https://developer.mozilla.org/en/HTML/Element/script#Attributes)
indicates that the script doesn't need to execute until the page has loaded,
speeding up page rendering; and the `onload` attribute calls
`renderMathInElement` once the auto-render script loads.

Alternatively, you can call the `renderMathInElement` when (or after) the
[`DOMContentLoaded` event](https://developer.mozilla.org/ko/docs/Web/Reference/Events/DOMContentLoaded)
fires on the document or in another deferred script.
This approach is useful for specifying or computing options, or if you don't
want to use a `defer` or `onload` attribute.
For example:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.22/dist/katex.min.css" integrity="sha384-5TcZemv2l/9On385z///+d7MSYlvIEw9FuZTIdZ14vJLqWphw7e7ZPuOiCHJcFCP" crossorigin="anonymous">
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.16.22/dist/katex.min.js" integrity="sha384-cMkvdD8LoxVzGF/RPUKAcvmm49FQ0oxwDF3BGKtDXcEc+T1b2N+teh/OJfpU0jr6" crossorigin="anonymous"></script>
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.16.22/dist/contrib/auto-render.min.js" integrity="sha384-hCXGrW6PitJEwbkoStFjeJxv+fSOOQKOPbJxSfM6G5sWZjAyWhXiTIIAmQqnlLlh" crossorigin="anonymous"></script>
<script>
    document.addEventListener("DOMContentLoaded", function() {
        renderMathInElement(document.body, {
          // customised options
          // • auto-render specific keys, e.g.:
          delimiters: [
              {left: '$$', right: '$$', display: true},
              {left: '$', right: '$', display: false},
              {left: '\\(', right: '\\)', display: false},
              {left: '\\[', right: '\\]', display: true}
          ],
          // • rendering keys, e.g.:
          throwOnError : false
        });
    });
</script>
```

ECMAScript module is also available:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.22/dist/katex.min.css" integrity="sha384-5TcZemv2l/9On385z///+d7MSYlvIEw9FuZTIdZ14vJLqWphw7e7ZPuOiCHJcFCP" crossorigin="anonymous">
<script type="module">
    import renderMathInElement from "https://cdn.jsdelivr.net/npm/katex@0.16.22/dist/contrib/auto-render.mjs";
    renderMathInElement(document.body);
</script>
```

> You can use [`nomodule` attribute](https://developer.mozilla.org/en/HTML/Element/script#Attributes)
to provide a fallback for older browsers that do not support ES modules.

## API
This extension exposes a single function, `window.renderMathInElement`, with
the following API:

```js
function renderMathInElement(elem, options)
```

`elem` is an HTML DOM element. The function will recursively search for text
nodes inside this element and render the math in them.

`options` is an optional object argument that can have the same keys as [the
object passed to `katex.render`](options.html),
in addition to five auto-render-specific keys:

- `delimiters`: This is a list of delimiters to look for math, processed in
  the same order as the list. Each delimiter has three properties:

    - `left`: A string which starts the math expression (i.e. the left delimiter).
    - `right`: A string which ends the math expression (i.e. the right delimiter).
    - `display`: A boolean of whether the math in the expression should be
      rendered in display mode or not.

  The default value is:

  ```js
  [
    {left: "$$", right: "$$", display: true},
    {left: "\\(", right: "\\)", display: false},
    {left: "\\begin{equation}", right: "\\end{equation}", display: true},
    {left: "\\begin{align}", right: "\\end{align}", display: true},
    {left: "\\begin{alignat}", right: "\\end{alignat}", display: true},
    {left: "\\begin{gather}", right: "\\end{gather}", display: true},
    {left: "\\begin{CD}", right: "\\end{CD}", display: true},
    {left: "\\[", right: "\\]", display: true}
  ]
  ```

  If you want to add support for inline math via `$...$`, be sure to list it
  *after* `$$`, as in the following. (Because rules are processed in order,
  putting a `$` rule first would catch `$$` as an empty math expression.)

  ```js
  [
    {left: "$$", right: "$$", display: true},
    {left: "$", right: "$", display: false},
    {left: "\\(", right: "\\)", display: false},
    {left: "\\[", right: "\\]", display: true}
  ]
  ```

- `ignoredTags`: This is a list of DOM node types to ignore when recursing
  through. The default value is
  `["script", "noscript", "style", "textarea", "pre", "code", "option"]`.

- `ignoredClasses`: This is a list of DOM node class names to ignore when
  recursing through. By default, this value is not set.

- `errorCallback`: A callback method returning a message and an error stack
  in case of an critical error during rendering. The default uses `console.error`.

- `preProcess`: A callback function, `(math: string) => string`, used to process
  math expressions before rendering.

The `displayMode` property of the options object is ignored, and is
instead taken from the `display` key of the corresponding entry in the
`delimiters` key.

The same `options.macros` object (which defaults to an empty object `{}`)
is passed into several calls to `katex.render`, so that consecutive equations
can build up shared macros by `\gdef`.
