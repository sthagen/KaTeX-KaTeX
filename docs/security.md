---
id: security
title: Security
---
Any HTML generated by KaTeX *should* be safe from `<script>` or other code
injection attacks.

Of course, it is always a good idea to sanitize the HTML, though you will need
a rather generous whitelist (including some of SVG and MathML) to support
all of KaTeX.

A variety of options give finer control over the security of KaTeX
with untrusted inputs; refer to [Options](options.md) for more details.
* `maxSize` can prevent large width/height visual affronts.
* `maxExpand` can prevent infinite macro loop attacks.
* `trust` can allow certain commands that may load external resources or change HTML attributes and thus are not always safe (e.g., `\includegraphics` or `\htmlClass`)

The error message thrown by KaTeX may contain unescaped LaTeX source code.
See [Handling Errors](error.md) for more details.

## Reporting a Vulnerability

If you have discovered a potential security issue with KaTeX:

1. Please report the issue privately by [opening a GitHub security advisory](https://github.com/KaTeX/KaTeX/security) or by emailing [katex-security@mit.edu](mailto:katex-security@mit.edu).
2. We will evaluate the vulnerability and, if necessary, release a fix and security advisory. We will credit you in the report, and invite you to collaborate on the solution and/or its evaluation.
3. Please do not disclose the vulnerability publicly until after a fix has been released.
