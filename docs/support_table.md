---
id: support_table
title: Support Table
---
This is a list of TeX functions, sorted alphabetically. This list includes functions that KaTeX supports and some that it doesn't support. There is a similar page, with functions [sorted by type](supported.md).

If you know the shape of a character, but not its name, [Detexify](https://detexify.kirelabs.org/classify.html) can help.

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.22/dist/katex.min.css" integrity="sha384-5TcZemv2l/9On385z///+d7MSYlvIEw9FuZTIdZ14vJLqWphw7e7ZPuOiCHJcFCP" crossorigin="anonymous">
<style>
table tr,
table td {
    vertical-align: middle;
}
</style>

## Symbols

$\gdef\VERT{|}$

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\!|$n!$|`n!`|
|\\\!|$a\!b$|`a\!b`|
|#|$\def\sqr#1{#1^2} \sqr{y}$|`\def\sqr#1{#1^2} \sqr{y}`|
|\\#|$\#$||
|%||`%this is a comment`|
|\\%|$\%$||
|&|$\begin{matrix} a & b\cr c & d \end{matrix}$|`\begin{matrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{matrix}`|
|\\&|$\&$||
|'|$'$||
|\\\'|$\text{\'{a}}$|`\text{\'{a}}`|
|(|$($||
|)|$)$||
|\\\(…\\\)|$\text{\(\frac a b\)}$|`\text{\(\frac a b\)}`|
|\\ |$a\ b$|`a\ b`|
|\\"|$\text{\"{a}}$|`\text{\"{a}}`|
|\\$|$\text{\textdollar}$||
|\\,|$a\,\,{b}$|`a\,\,{b}`|
|\\.|$\text{\.{a}}$|`\text{\.{a}}`|
|\\:|$a\:\:{b}$|`a\:\:{b}`|
|\\;|$a\;\;{b}$|a`\;\;{b}`|
|_|$x_i$|`x_i`|
|\\_|$\_$||
|\\\`|$\text{\`{a}}$|`\text{\'{a}}`|
|&#060;|$<$||
|\\=|$\text{\={a}}$|`\text{\={a}}`|
| >|$>$||
|\\>|$a\>\>{b}$|`a\>\>{b}`|
|\[|$[$||
|\]|$]$||
|{|${a}$|`{a}`|
|}|${a}$|`{a}`|
|\\{|$\{$||
|\\}|$\}$||
|&#124;|$\vert$||
|\\&#124;|$\Vert$||
|~|$\text{no~no~no~breaks}$|`\text{no~no~no~breaks}`|
|\\~|$\text{\~{a}}$|`\text{\~{a}}`|
|\\\\ |$\begin{matrix} a & b\\ c & d\end{matrix}$|`\begin{matrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{matrix}`|
|^|$x^i$|`x^i`|
|\\^|$\text{\^{a}}$|`\text{\^{a}}`|

## A

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\AA|$\text{\AA}$|`\text{\AA}`|
|\aa|$\text{\aa}$|`\text{\aa}`|
|\above|${a \above{2pt} b+1}$|`{a \above{2pt} b+1}`|
|\abovewithdelims|<span style="color:firebrick;">Not supported</span>||
|\acute|$\acute e$|`\acute e`|
|\AE|$\text{\AE}$|`\text{\AE}`|
|\ae|$\text{\ae}$|`\text{\ae}`|
|\alef|$\alef$||
|\alefsym|$\alefsym$||
|\aleph|$\aleph$||
|{align}|$$\begin{align}a&=b+c\\d+e&=f\end{align}$$|`\begin{align}`<br>&nbsp;&nbsp;&nbsp;`a&=b+c \\`<br>&nbsp;&nbsp;&nbsp;`d+e&=f`<br>`\end{align}`|
|{align\*}|$$\begin{align*}a&=b+c\\d+e&=f\end{align*}$$|`\begin{align*}`<br>&nbsp;&nbsp;&nbsp;`a&=b+c \\`<br>&nbsp;&nbsp;&nbsp;`d+e&=f`<br>`\end{align*}`|
|{aligned}|$\begin{aligned}a&=b+c\\d+e&=f\end{aligned}$|`\begin{aligned}`<br>&nbsp;&nbsp;&nbsp;`a&=b+c \\`<br>&nbsp;&nbsp;&nbsp;`d+e&=f`<br>`\end{aligned}`|
|{alignat}|$$\begin{alignat}{2}10&x+&3&y=2\\3&x+&13&y=4\end{alignat}$$|`\begin{alignat}{2}`<br>&nbsp;&nbsp;&nbsp;`10&x+ &3&y = 2 \\`<br>&nbsp;&nbsp;&nbsp;` 3&x+&13&y = 4`<br>`\end{alignat}`|
|{alignat\*}|$$\begin{alignat*}{2}10&x+&3&y=2\\3&x+&13&y=4\end{alignat*}$$|`\begin{alignat*}{2}`<br>&nbsp;&nbsp;&nbsp;`10&x+ &3&y = 2 \\`<br>&nbsp;&nbsp;&nbsp;` 3&x+&13&y = 4`<br>`\end{alignat*}`|
|{alignedat}|$\begin{alignedat}{2}10&x+&3&y=2\\3&x+&13&y=4\end{alignedat}$|`\begin{alignedat}{2}`<br>&nbsp;&nbsp;&nbsp;`10&x+ &3&y = 2 \\`<br>&nbsp;&nbsp;&nbsp;` 3&x+&13&y = 4`<br>`\end{alignedat}`|
|\allowbreak|||
|\Alpha|$\Alpha$||
|\alpha|$\alpha$||
|\amalg|$\amalg$||
|\And|$\And$||
|\and|<span style="color:firebrick;">Not supported</span>|[Deprecated](https://en.wikipedia.org/wiki/Help:Displaying_a_formula#Deprecated_syntax)|
|\ang|<span style="color:firebrick;">Not supported</span>|[Deprecated](https://en.wikipedia.org/wiki/Help:Displaying_a_formula#Deprecated_syntax)|
|\angl|$a_{\angl n}$||
|\angln|$a_\angln$||
|\angle|$\angle$||
|\approx|$\approx$||
|\approxeq|$\approxeq$||
|\approxcolon|$\approxcolon$||
|\approxcoloncolon|$\approxcoloncolon$||
|\arccos|$\arccos$||
|\arcctg|$\arcctg$||
|\arcsin|$\arcsin$||
|\arctan|$\arctan$||
|\arctg|$\arctg$||
|\arg|$\arg$||
|\argmax|$\argmax$||
|\argmin|$\argmin$||
|{array}|$\begin{array}{cc}a&b\\c&d\end{array}$ | `\begin{array}{cc}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{array}`|
|\array|<span style="color:firebrick;">Not supported</span>|see `{array}`|
|\arraystretch|$\def\arraystretch{1.5}\begin{array}{cc}a&b\\c&d\end{array}$|`\def\arraystretch{1.5}`<br>`\begin{array}{cc}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{array}`|
|\Arrowvert|<span style="color:firebrick;">Not supported</span>|see `\Vert`|
|\arrowvert|<span style="color:firebrick;">Not supported</span>|see `\vert`|
|\ast|$\ast$||
|\asymp|$\asymp$||
|\atop|${a \atop b}$|`{a \atop b}`|
|\atopwithdelims|<span style="color:firebrick;">Not supported</span>||

## B

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\backepsilon|$\backepsilon$||
|\backprime|$\backprime$||
|\backsim|$\backsim$||
|\backsimeq|$\backsimeq$||
|\backslash|$\backslash$||
|\bar|$\bar{y}$|`\bar{y}`|
|\barwedge|$\barwedge$||
|\Bbb|$\Bbb{ABC}$|`\Bbb{ABC}`<br>KaTeX supports A-Z & k|
|\Bbbk|$\Bbbk$||
|\bbox|<span style="color:firebrick;">Not supported</span>||
|\bcancel|$\bcancel{5}$|`\bcancel{5}`|
|\because|$\because$||
|\begin|$\begin{matrix} a & b\\ c & d\end{matrix}$|`\begin{matrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{matrix}`|
|\begingroup|$\begingroup a}$|`\begingroup a}`|
|\Beta|$\Beta$||
|\beta|$\beta$||
|\beth|$\beth$||
|\between|$\between$||
|\bf|$\bf AaBb12$|`\bf AaBb12`|
|\bfseries|<span style="color:firebrick;">Not supported</span>||
|\big|$\big(\big)$|`\big(\big)`|
|\Big|$\Big(\Big)$|`\Big(\Big)`|
|\bigcap|$\bigcap$||
|\bigcirc|$\bigcirc$||
|\bigcup|$\bigcup$||
|\bigg|$\bigg(\bigg)$|`\bigg(\bigg)`|
|\Bigg|$\Bigg(\Bigg)$|`\Bigg(\Bigg)`|
|\biggl|$\biggl($|`\biggl(`|
|\Biggl|$\Biggl($|`\Biggl(`|
|\biggm|$\biggm\vert$|`\biggm\vert`|
|\Biggm|$\Biggm\vert$|`\Biggm\vert`|
|\biggr|$\biggr)$|`\biggr)`|
|\Biggr|$\Biggr)$|`\Biggr)`|
|\bigl|$\bigl($|`\bigl(`|
|\Bigl|$\Bigl($|`\Bigl(`|
|\bigm|$\bigm\vert$|`\bigm\vert`|
|\Bigm|$\Bigm\vert$|`\Bigm\vert`|
|\bigodot|$\bigodot$||
|\bigominus|<span style="color:firebrick;">Not supported</span>|[Issue #1222](https://github.com/KaTeX/KaTeX/issues/1222)|
|\bigoplus|$\bigoplus$||
|\bigoslash|<span style="color:firebrick;">Not supported</span>|[Issue #1222](https://github.com/KaTeX/KaTeX/issues/1222)|
|\bigotimes|$\bigotimes$||
|\bigr|$\bigr)$|`\bigr)`|
|\Bigr|$\Bigr)$|`\Bigr)`|
|\bigsqcap|<span style="color:firebrick;">Not supported</span>|[Issue #1222](https://github.com/KaTeX/KaTeX/issues/1222)|
|\bigsqcup|$\bigsqcup$||
|\bigstar|$\bigstar$||
|\bigtriangledown|$\bigtriangledown$||
|\bigtriangleup|$\bigtriangleup$||
|\biguplus|$\biguplus$||
|\bigvee|$\bigvee$||
|\bigwedge|$\bigwedge$||
|\binom|$\binom n k$|`\binom n k`|
|\blacklozenge|$\blacklozenge$||
|\blacksquare|$\blacksquare$||
|\blacktriangle|$\blacktriangle$||
|\blacktriangledown|$\blacktriangledown$||
|\blacktriangleleft|$\blacktriangleleft$||
|\blacktriangleright|$\blacktriangleright$||
|\bm|$\bm{AaBb}$|`\bm{AaBb}`|
|{Bmatrix}|$\begin{Bmatrix}a&b\\c&d\end{Bmatrix}$|`\begin{Bmatrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{Bmatrix}`|
|{Bmatrix*}|$\begin{Bmatrix*}[r]0&-1\\-1&0\end{Bmatrix*}$|`\begin{Bmatrix*}[r]`<br>&nbsp;&nbsp;&nbsp;`0 & -1 \\`<br>&nbsp;&nbsp;&nbsp;`-1 & 0`<br>`\end{Bmatrix*}`|
|{bmatrix}|$\begin{bmatrix}a&b\\c&d\end{bmatrix}$|`\begin{bmatrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{bmatrix}`|
|{bmatrix*}|$\begin{bmatrix*}[r]0&-1\\-1&0\end{bmatrix*}$|`\begin{bmatrix*}[r]`<br>&nbsp;&nbsp;&nbsp;`0 & -1 \\`<br>&nbsp;&nbsp;&nbsp;`-1 & 0`<br>`\end{bmatrix*}`|
|\bmod|$a \bmod b$|`a \bmod b`|
|\bold|$\bold{AaBb123}$|`\bold{AaBb123}`|
|\boldsymbol|$\boldsymbol{AaBb}$|`\boldsymbol{AaBb}`|
|\bot|$\bot$||
|\bowtie|$\bowtie$||
|\Box|$\Box$||
|\boxdot|$\boxdot$||
|\boxed|$\boxed{ab}$|`\boxed{ab}`|
|\boxminus|$\boxminus$||
|\boxplus|$\boxplus$||
|\boxtimes|$\boxtimes$||
|\Bra|$\Bra{\psi}$|`\Bra{\psi}`|
|\bra|$\bra{\psi}$|`\bra{\psi}`|
|\braket|$\braket{\phi\VERT\psi}$|<code>\braket{\phi&#124;\psi}</code>|
|\Braket|$\Braket{ ϕ \VERT \frac{∂^2}{∂ t^2} \VERT ψ }$| <code>\Braket{ ϕ &#124; \frac{∂^2}{∂ t^2} &#124; ψ }</code>|
|\brace|${n\brace k}$|`{n\brace k}`|
|\bracevert|<span style="color:firebrick;">Not supported</span>||
|\brack|${n\brack k}$|`{n\brack k}`|
|\breve|$\breve{eu}$|`\breve{eu}`|
|\buildrel|<span style="color:firebrick;">Not supported</span>||
|\bull|$\bull$||
|\bullet|$\bullet$||
|\Bumpeq|$\Bumpeq$||
|\bumpeq|$\bumpeq$||

## C

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\C|<span style="color:firebrick;">Not supported</span>|[Deprecated](https://en.wikipedia.org/wiki/Help:Displaying_a_formula#Deprecated_syntax)|
|\cal|$\cal AaBb123$|`\cal AaBb123`|
|\cancel|$\cancel{5}$|`\cancel{5}`|
|\cancelto|<span style="color:firebrick;">Not supported</span>||
|\Cap|$\Cap$||
|\cap|$\cap$||
|{cases}|$\begin{cases}a&\text{if }b\\c&\text{if }d\end{cases}$|`\begin{cases}`<br>&nbsp;&nbsp;&nbsp;`a &\text{if } b  \\`<br>&nbsp;&nbsp;&nbsp;`c &\text{if } d`<br>`\end{cases}`|
|\cases|<span style="color:firebrick;">Not supported</span>|see `{cases}`|
|{CD}|$$\begin{CD}A @>a>> B \\@VbVV @AAcA\\C @= D\end{CD}$$|`\begin{CD}`<br>&nbsp;&nbsp;&nbsp;`A  @>a>>  B  \\`<br>`@VbVV    @AAcA \\`<br>&nbsp;&nbsp;&nbsp;`C  @=     D`<br>`\end{CD}`|
|\cdot|$\cdot$||
|\cdotp|$\cdotp$||
|\cdots|$\cdots$||
|\ce |${\mathrm{C}{\vphantom{X}}_{\smash[t]{6}}\mathrm{H}{\vphantom{X}}_{\smash[t]{5}}{-}\mathrm{CHO}}$|`\ce{C6H5-CHO}` Requires an [extension](https://github.com/KaTeX/KaTeX/tree/main/contrib/mhchem/)|
|\cee|<span style="color:firebrick;">Not supported</span>|Deprecated by mhchem
|\centerdot|$a\centerdot b$|`a\centerdot b`|
|\cf|<span style="color:firebrick;">Not supported</span>|Deprecated by mhchem;
use `\ce` instead|
|\cfrac|$\cfrac{2}{1+\cfrac{2}{1+\cfrac{2}{1}}}$|`\cfrac{2}{1+\cfrac{2}{1+\cfrac{2}{1}}}`|
|\char|$\char"263a$|`\char"263a`|
|\check|$\check{oe}$|`\check{oe}`|
|\ch|$\ch$||
|\checkmark|$\checkmark$||
|\Chi|$\Chi$||
|\chi|$\chi$||
|\choose|${n+1 \choose k+2}$|`{n+1 \choose k+2}`|
|\circ|$\circ$||
|\circeq|$\circeq$||
|\circlearrowleft|$\circlearrowleft$||
|\circlearrowright|$\circlearrowright$||
|\circledast|$\circledast$||
|\circledcirc|$\circledcirc$||
|\circleddash|$\circleddash$||
|\circledR|$\circledR$||
|\circledS|$\circledS$||
|\class|<span style="color:firebrick;">Not supported</span>|A PR is pending.
|\cline|<span style="color:firebrick;">Not supported</span>|[Issue #269](https://github.com/KaTeX/KaTeX/issues/269)|
|\clubs|$\clubs$||
|\clubsuit|$\clubsuit$||
|\cnums|$\cnums$||
|\colon|$\colon$||
|\Colonapprox|$\Colonapprox$||
|\colonapprox|$\colonapprox$||
|\coloncolon|$\coloncolon$||
|\coloncolonapprox|$\coloncolonapprox$||
|\coloncolonequals|$\coloncolonequals$||
|\coloncolonminus|$\coloncolonminus$||
|\coloncolonsim|$\coloncolonsim$||
|\Coloneq|$\Coloneq$||
|\coloneq|$\coloneq$||
|\colonequals|$\colonequals$||
|\Coloneqq|$\Coloneqq$||
|\coloneqq|$\coloneqq$||
|\colonminus|$\colonminus$||
|\Colonsim|$\Colonsim$||
|\colonsim|$\colonsim$||
|\color|$\color{#0000FF} AaBb123$|`\color{#0000FF} AaBb123`|
|\colorbox|$\colorbox{red}{Black on red}$|`\colorbox{red}{Black on red}`|
|\complement|$\complement$||
|\Complex|$\Complex$||
|\cong|$\cong$||
|\Coppa|<span style="color:firebrick;">Not supported</span>||
|\coppa|<span style="color:firebrick;">Not supported</span>||
|\coprod|$\coprod$||
|\copyright|$\copyright$||
|\cos|$\cos$||
|\cosec|$\cosec$||
|\cosh|$\cosh$||
|\cot|$\cot$||
|\cotg|$\cotg$||
|\coth|$\coth$||
|\cr|$\begin{matrix} a & b\cr c & d \end{matrix}$|`\begin{matrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \cr`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{matrix}`|
|\csc|$\csc$||
|\cssId|<span style="color:firebrick;">Not supported</span>|A PR is pending.
|\ctg|$\ctg$||
|\cth|$\cth$||
|\Cup|$\Cup$||
|\cup|$\cup$||
|\curlyeqprec|$\curlyeqprec$||
|\curlyeqsucc|$\curlyeqsucc$||
|\curlyvee|$\curlyvee$||
|\curlywedge|$\curlywedge$||
|\curvearrowleft|$\curvearrowleft$||
|\curvearrowright|$\curvearrowright$||

## D

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\dag|$\dag$||
|\Dagger|$\Dagger$||
|\dagger|$\dagger$||
|\daleth|$\daleth$||
|\Darr|$\Darr$||
|\dArr|$\dArr$||
|\darr|$\darr$||
{darray}|$\begin{darray}{cc}a&b\\c&d\end{darray}$ | `\begin{darray}{cc}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{darray}`|
|\dashleftarrow|$\dashleftarrow$||
|\dashrightarrow|$\dashrightarrow$||
|\dashv|$\dashv$||
|\dbinom|$\dbinom n k$|`\dbinom n k`|
|\dblcolon|$\dblcolon$||
|{dcases}|$\begin{dcases}a&\text{if }b\\c&\text{if }d\end{dcases}$|`\begin{dcases}`<br>&nbsp;&nbsp;&nbsp;`a &\text{if } b  \\`<br>&nbsp;&nbsp;&nbsp;`c &\text{if } d`<br>`\end{dcases}`|
|\ddag|$\ddag$||
|\ddagger|$\ddagger$||
|\ddddot|$\ddddot x$|`\ddddot x`|
|\dddot|$\dddot x$|`\dddot x`|
|\ddot|$\ddot x$|`\ddot x`|
|\ddots|$\ddots$||
|\DeclareMathOperator|<span style="color:firebrick;">Not supported</span>||
|\def|$\def\foo{x^2} \foo + \foo$|`\def\foo{x^2} \foo + \foo`|
|\definecolor|<span style="color:firebrick;">Not supported</span>|[Issue #750](https://github.com/KaTeX/KaTeX/issues/750)|
|\deg|$\deg$||
|\degree|$\degree$||
|\delta|$\delta$||
|\Delta|$\Delta$||
|\det|$\det$||
|\Digamma|<span style="color:firebrick;">Not supported</span>||
|\digamma|$\digamma$||
|\dfrac|$\dfrac{a-1}{b-1}$|`\dfrac{a-1}{b-1}`|
|\diagdown|$\diagdown$||
|\diagup|$\diagup$||
|\Diamond|$\Diamond$||
|\diamond|$\diamond$||
|\diamonds|$\diamonds$||
|\diamondsuit|$\diamondsuit$||
|\dim|$\dim$||
|\displaylines|<span style="color:firebrick;">Not supported</span>||
|\displaystyle|$\displaystyle\sum_0^n$|`\displaystyle\sum_0^n`|
|\div|$\div$||
|\divideontimes|$\divideontimes$||
|\dot|$\dot x$|`\dot x`|
|\Doteq|$\Doteq$||
|\doteq|$\doteq$||
|\doteqdot|$\doteqdot$||
|\dotplus|$\dotplus$||
|\dots|$x_1 + \dots + x_n$|`x_1 + \dots + x_n`|
|\dotsb|$x_1 +\dotsb + x_n$|`x_1 +\dotsb + x_n`|
|\dotsc|$x,\dotsc,y$|`x,\dotsc,y`|
|\dotsi|$$\int_{A_1}\int_{A_2}\dotsi$$|`\int_{A_1}\int_{A_2}\dotsi`|
|\dotsm|$x_1 x_2 \dotsm x_n$|`$x_1 x_2 \dotsm x_n`|
|\dotso|$\dotso$||
|\doublebarwedge|$\doublebarwedge$||
|\doublecap|$\doublecap$||
|\doublecup|$\doublecup$||
|\Downarrow|$\Downarrow$||
|\downarrow|$\downarrow$||
|\downdownarrows|$\downdownarrows$||
|\downharpoonleft|$\downharpoonleft$||
|\downharpoonright|$\downharpoonright$||
|{drcases}|$\begin{drcases}a&\text{if }b\\c&\text{if }d\end{drcases}$|`\begin{drcases}`<br>&nbsp;&nbsp;&nbsp;`a &\text{if } b  \\`<br>&nbsp;&nbsp;&nbsp;`c &\text{if } d`<br>`\end{drcases}`|

## E

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\edef|$\def\foo{a}\edef\fcopy{\foo}\def\foo{}\fcopy$|`\def\foo{a}\edef\fcopy{\foo}\def\foo{}\fcopy`|
|\ell|$\ell$||
|\else|<span style="color:firebrick;">Not supported</span>|[Issue #1003](https://github.com/KaTeX/KaTeX/issues/1003)|
|\em|<span style="color:firebrick;">Not supported</span>||
|\emph|$\emph{nested \emph{emphasis}}$|`\emph{nested \emph{emphasis}}`|
|\empty|$\empty$||
|\emptyset|$\emptyset$||
|\enclose|<span style="color:firebrick;">Not supported</span>|Non standard
|\end|$\begin{matrix} a & b\\ c & d\end{matrix}$|`\begin{matrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{matrix}`|
|\endgroup|${a\endgroup$|`{a\endgroup`|
|\enspace|$a\enspace b$|`a\enspace b`|
|\Epsilon|$\Epsilon$||
|\epsilon|$\epsilon$||
|\eqalign|<span style="color:firebrick;">Not supported</span>||
|\eqalignno|<span style="color:firebrick;">Not supported</span>||
|\eqcirc|$\eqcirc$||
|\Eqcolon|$\Eqcolon$||
|\eqcolon|$\eqcolon$||
|{equation}|$$\begin{equation}a = b + c\end{equation}$$|`\begin{equation}`<br>&nbsp;&nbsp;&nbsp;`a = b + c`<br>`\end{equation}`|
|{equation*}|$$\begin{equation*}a = b + c\end{equation*}$$|`\begin{equation*}`<br>&nbsp;&nbsp;&nbsp;`a = b + c`<br>`\end{equation*}`|
|{eqnarray}|<span style="color:firebrick;">Not supported</span>||
|\Eqqcolon|$\Eqqcolon$||
|\eqqcolon|$\eqqcolon$||
|\eqref|<span style="color:firebrick;">Not supported</span>|[Issue #350](https://github.com/KaTeX/KaTeX/issues/350)|
|\eqsim|$\eqsim$||
|\eqslantgtr|$\eqslantgtr$||
|\eqslantless|$\eqslantless$||
|\equalscolon|$\equalscolon$||
|\equalscoloncolon|$\equalscoloncolon$||
|\equiv|$\equiv$||
|\Eta|$\Eta$||
|\eta|$\eta$||
|\eth|$\eth$||
|\euro|<span style="color:firebrick;">Not supported</span>||
|\exist|$\exist$||
|\exists|$\exists$||
|\exp|$\exp$||
|\expandafter|||

## F

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\fallingdotseq|$\fallingdotseq$||
|\fbox|$\fbox{Hi there!}$|`\fbox{Hi there!}`|
|\fcolorbox|$\fcolorbox{red}{aqua}{A}$|`\fcolorbox{red}{aqua}{A}`|
|\fi|<span style="color:firebrick;">Not supported</span>|[Issue #1003](https://github.com/KaTeX/KaTeX/issues/1003)|
|\Finv|$\Finv$||
|\flat|$\flat$||
|\footnotesize|$\footnotesize footnotesize$|`\footnotesize footnotesize`|
|\forall|$\forall$||
|\frac|$\frac a b$|`\frac a b`|
|\frak|$\frak{AaBb}$|`\frak{AaBb}`|
|\frown|$\frown$||
|\futurelet|||

## G

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\Game|$\Game$||
|\Gamma|$\Gamma$||
|\gamma|$\gamma$||
|{gather}|$$\begin{gather}a=b\\e=b+c\end{gather}$$|`\begin{gather}`<br>&nbsp;&nbsp;&nbsp;`a=b \\ `<br>&nbsp;&nbsp;&nbsp;`e=b+c`<br>`\end{gather}`|
|{gathered}|$\begin{gathered}a=b\\e=b+c\end{gathered}$|`\begin{gathered}`<br>&nbsp;&nbsp;&nbsp;`a=b \\ `<br>&nbsp;&nbsp;&nbsp;`e=b+c`<br>`\end{gathered}`|
|\gcd|$\gcd$||
|\gdef|$\gdef\sqr#1{#1^2} \sqr{y} + \sqr{y}$|`\gdef\sqr#1{#1^2} \sqr{y} + \sqr{y}`|
|\ge|$\ge$||
|\geneuro|<span style="color:firebrick;">Not supported</span>||
|\geneuronarrow|<span style="color:firebrick;">Not supported</span>||
|\geneurowide|<span style="color:firebrick;">Not supported</span>||
|\genfrac|$\genfrac ( ] {2pt}{0}a{a+1}$|`\genfrac ( ] {2pt}{0}a{a+1}`|
|\geq|$\geq$||
|\geqq|$\geqq$||
|\geqslant|$\geqslant$||
|\gets|$\gets$||
|\gg|$\gg$||
|\ggg|$\ggg$||
|\gggtr|$\gggtr$||
|\gimel|$\gimel$||
|\global|$\global\def\add#1#2{#1+#2} \add 2 3$|`\global\def\add#1#2{#1+#2} \add 2 3`|
|\gnapprox|$\gnapprox$||
|\gneq|$\gneq$||
|\gneqq|$\gneqq$||
|\gnsim|$\gnsim$||
|\grave|$\grave{eu}$|`\grave{eu}`|
|\gt|$a \gt b$|`a \gt b`|
|\gtrdot|$\gtrdot$||
|\gtrapprox|$\gtrapprox$||
|\gtreqless|$\gtreqless$||
|\gtreqqless|$\gtreqqless$||
|\gtrless|$\gtrless$||
|\gtrsim|$\gtrsim$||
|\gvertneqq|$\gvertneqq$||

## H

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\H|$\text{\H{a}}$|`\text{\H{a}}`|
|\Harr|$\Harr$||
|\hArr|$\hArr$||
|\harr|$\harr$||
|\hat|$\hat{\theta}$|`\hat{\theta}`|
|\hbar|$\hbar$||
|\hbox|$\hbox{$x^2$}$|`\hbox{$x^2$}`|
|\hbox to <dimen>| <span style="color:firebrick;">Not supported</span> ||
|\hdashline|$\begin{matrix}a&b\\ \hdashline c &d\end{matrix}$|`\begin{matrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`\hdashline`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{matrix}`|
|\hearts|$\hearts$||
|\heartsuit|$\heartsuit$||
|\hfil|<span style="color:firebrick;">Not supported</span>||
|\hfill|<span style="color:firebrick;">Not supported</span>|Issues [#164](https://github.com/KaTeX/KaTeX/issues/164) & [#269](https://github.com/KaTeX/KaTeX/issues/269)|
|\hline|$\begin{matrix}a&b\\ \hline c &d\end{matrix}$|`\begin{matrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\ \hline`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{matrix}`|
|\hom|$\hom$||
|\hookleftarrow|$\hookleftarrow$||
|\hookrightarrow|$\hookrightarrow$||
|\hphantom|$a\hphantom{bc}d$|`a\hphantom{bc}d`|
|\href|$\href{https://katex.org/}{\KaTeX}$|`\href{https://katex.org/}{\KaTeX}` Requires `trust` [option](options.md)|
|\hskip|$w\hskip1em i\hskip2em d$|`w\hskip1em i\hskip2em d`|
|\hslash|$\hslash$||
|\hspace|$s\hspace7ex k$|`s\hspace7ex k`|
|\htmlClass|$\htmlClass{foo}{x}$|`\htmlClass{foo}{x}` Must enable `trust` and disable `strict` [option](options.md)|
|\htmlData|$\htmlData{foo=a, bar=b}{x}$|`\htmlData{foo=a, bar=b}{x}` Must enable `trust` and disable `strict` [option](options.md)|
|\htmlId|$\htmlId{bar}{x}$|`\htmlId{bar}{x}` Must enable `trust` and disable `strict` [option](options.md)|
|\htmlStyle|$\htmlStyle{color: red;}{x}$|`\htmlStyle{color: red;}{x}` Must enable `trust` and disable `strict` [option](options.md)|
|\huge|$\huge huge$|`\huge huge`|
|\Huge|$\Huge Huge$|`\Huge Huge`|

## I

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\i|$\text{\i}$|`\text{\i}`|
|\idotsint|<span style="color:firebrick;">Not supported</span>||
|\iddots|<span style="color:firebrick;">Not supported</span>|[Issue #1223](https://github.com/KaTeX/KaTeX/issues/1223)|
|\if|<span style="color:firebrick;">Not supported</span>|[Issue #1003](https://github.com/KaTeX/KaTeX/issues/1003)|
|\iff|$A\iff B$|`A\iff B`|
|\ifmode|<span style="color:firebrick;">Not supported</span>|[Issue #1003](https://github.com/KaTeX/KaTeX/issues/1003)|
|\ifx|<span style="color:firebrick;">Not supported</span>|[Issue #1003](https://github.com/KaTeX/KaTeX/issues/1003)|
|\iiiint|<span style="color:firebrick;">Not supported</span>||
|\iiint|$\iiint$||
|\iint|$\iint$||
|\Im|$\Im$||
|\image|$\image$||
|\imageof|$\imageof$||
|\imath|$\imath$||
|\impliedby|$P\impliedby Q$|`P\impliedby Q`|
|\implies|$P\implies Q$|`P\implies Q`|
|\in|$\in$||
|\includegraphics|$\includegraphics[height=0.8em, totalheight=0.9em, width=0.9em, alt=KA logo]{https://cdn.kastatic.org/images/apple-touch-icon-57x57-precomposed.new.png}$|`\includegraphics[height=0.8em, totalheight=0.9em, width=0.9em, alt=KA logo]{https://cdn.kastatic.org/images/apple-touch-icon-57x57-precomposed.new.png}` Requires `trust` [option](options.md)
|\inf|$\inf$||
|\infin|$\infin$||
|\infty|$\infty$||
|\injlim|$\injlim$| `\injlim` |
|\int|$\int$||
|\intercal|$\intercal$||
|\intop|$\intop$||
|\Iota|$\Iota$||
|\iota|$\iota$||
|\isin|$\isin$||
|\it|${\it AaBb}$|`{\it AaBb}`|
|\itshape|<span style="color:firebrick;">Not supported</span>||

## JK

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\j|$\text{\j}$|`\text{\j}`|
|\jmath|$\jmath$||
|\Join|$\Join$||
|\Kappa|$\Kappa$||
|\kappa|$\kappa$||
|\KaTeX|$\KaTeX$||
|\ker|$\ker$||
|\kern|$I\kern-2.5pt R$|`I\kern-2.5pt R`|
|\Ket|$\Ket{\psi}$|`\Ket{\psi}`|
|\ket|$\ket{\psi}$|`\ket{\psi}`|
|\Koppa|<span style="color:firebrick;">Not supported</span>||
|\koppa|<span style="color:firebrick;">Not supported</span>||

## L

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\L|<span style="color:firebrick;">Not supported</span>||
|\l|<span style="color:firebrick;">Not supported</span>||
|\Lambda|$\Lambda$||
|\lambda|$\lambda$||
|\label|<span style="color:firebrick;">Not supported</span>||
|\land|$\land$||
|\lang|$\lang A\rangle$|`\lang A\rangle`|
|\langle|$\langle A\rangle$|`\langle A\rangle`|
|\Larr|$\Larr$||
|\lArr|$\lArr$||
|\larr|$\larr$||
|\large|$\large large$|`\large large`|
|\Large|$\Large Large$|`\Large Large`|
|\LARGE|$\LARGE LARGE$|`\LARGE LARGE`|
|\LaTeX|$\LaTeX$||
|\lBrace|$\lBrace$||
|\lbrace|$\lbrace$||
|\lbrack|$\lbrack$||
|\lceil|$\lceil$||
|\ldotp|$\ldotp$||
|\ldots|$\ldots$||
|\le|$\le$||
|\leadsto|$\leadsto$||
|\left|$\left\lbrace \dfrac ab \right.$|`\left\lbrace \dfrac ab \right.`|
|\leftarrow|$\leftarrow$||
|\Leftarrow|$\Leftarrow$||
|\LeftArrow|<span style="color:firebrick;">Not supported</span>|Non standard
|\leftarrowtail|$\leftarrowtail$||
|\leftharpoondown|$\leftharpoondown$||
|\leftharpoonup|$\leftharpoonup$||
|\leftleftarrows|$\leftleftarrows$||
|\Leftrightarrow|$\Leftrightarrow$||
|\leftrightarrow|$\leftrightarrow$||
|\leftrightarrows|$\leftrightarrows$||
|\leftrightharpoons|$\leftrightharpoons$||
|\leftrightsquigarrow|$\leftrightsquigarrow$||
|\leftroot|<span style="color:firebrick;">Not supported</span>||
|\leftthreetimes|$\leftthreetimes$||
|\leq|$\leq$||
|\leqalignno|<span style="color:firebrick;">Not supported</span>||
|\leqq|$\leqq$||
|\leqslant|$\leqslant$||
|\lessapprox|$\lessapprox$||
|\lessdot|$\lessdot$||
|\lesseqgtr|$\lesseqgtr$||
|\lesseqqgtr|$\lesseqqgtr$||
|\lessgtr|$\lessgtr$||
|\lesssim|$\lesssim$||
|\let|||
|\lfloor|$\lfloor$||
|\lg|$\lg$||
|\lgroup|$\lgroup$||
|\lhd|$\lhd$||
|\lim|$\lim$||
|\liminf|$\liminf$||
|\limits|$\lim\limits_x$|`\lim\limits_x`|
|\limsup|$\limsup$||
|\ll|$\ll$||
|\llap|${=}\llap{/\,}$|`{=}\llap{/\,}`|
|\llbracket|$\llbracket$||
|\llcorner|$\llcorner$||
|\Lleftarrow|$\Lleftarrow$||
|\lll|$\lll$||
|\llless|$\llless$||
|\lmoustache|$\lmoustache$||
|\ln|$\ln$||
|\lnapprox|$\lnapprox$||
|\lneq|$\lneq$||
|\lneqq|$\lneqq$||
|\lnot|$\lnot$||
|\lnsim|$\lnsim$||
|\log|$\log$||
|\long|||
|\Longleftarrow|$\Longleftarrow$||
|\longleftarrow|$\longleftarrow$||
|\Longleftrightarrow|$\Longleftrightarrow$||
|\longleftrightarrow|$\longleftrightarrow$||
|\longmapsto|$\longmapsto$||
|\Longrightarrow|$\Longrightarrow$||
|\longrightarrow|$\longrightarrow$||
|\looparrowleft|$\looparrowleft$||
|\looparrowright|$\looparrowright$||
|\lor|$\lor$||
|\lower|<span style="color:firebrick;">Not supported</span>||
|\lozenge|$\lozenge$||
|\lparen|$\lparen$||
|\Lrarr|$\Lrarr$||
|\lrArr|$\lrArr$||
|\lrarr|$\lrarr$||
|\lrcorner|$\lrcorner$||
|\lq|$\lq$||
|\Lsh|$\Lsh$||
|\lt|$\lt$||
|\ltimes|$\ltimes$||
|\lVert|$\lVert$||
|\lvert|$\lvert$||
|\lvertneqq|$\lvertneqq$||

## M

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\maltese|$\maltese$||
|\mapsto|$\mapsto$||
|\mathbb|$\mathbb{AB}$|`\mathbb{AB}`<br>KaTeX supports A-Z k|
|\mathbf|$\mathbf{AaBb123}$|`\mathbf{AaBb123}`|
|\mathbin|$a\mathbin{!}b$|`a\mathbin{!}b`|
|\mathcal|$\mathcal{AaBb123}$|`\mathcal{AaBb123}`|
|\mathchoice|$a\mathchoice{\,}{\,\,}{\,\,\,}{\,\,\,\,}b$|`a\mathchoice{\,}{\,\,}{\,\,\,}{\,\,\,\,}b`|
|\mathclap|$\displaystyle\sum_{\mathclap{1\le i\le n}} x_{i}$|`\sum_{\mathclap{1\le i\le n}} x_{i}`|
|\mathclose|$a + (b\mathclose\gt + c$|`a + (b\mathclose\gt + c`|
|\mathellipsis|$\mathellipsis$||
|\mathfrak|$\mathfrak{AaBb}$|`\mathfrak{AaBb}`<br>KaTeX supports A-Za-z|
|\mathinner|$ab\mathinner{\text{inside}}cd$|`ab\mathinner{\text{inside}}cd`|
|\mathit|$\mathit{AaBb}$|`\mathit{AaBb}`<br>KaTeX supports A-Za-z|
|\mathllap|${=}\mathllap{/\,}$|`{=}\mathllap{/\,}`|
|\mathnormal|$\mathnormal{AaBb}$|`\mathnormal{AaBb}`<br>KaTeX supports A-Za-z|
|\mathop|$\mathop{\star}_a^b$|`\mathop{\star}_a^b`|
|\mathopen|$a + \mathopen\lt b) + c$|`a + \mathopen\lt b) + c`|
|\mathord|$1\mathord{,}234{,}567$|`1\mathord{,}234{,}567`|
|\mathpunct|$A\mathpunct{-}B$|`A\mathpunct{-}B`|
|\mathrel|$a \mathrel{\#} b$|`a \mathrel{\#} b`|
|\mathrlap|$\mathrlap{\,/}{=}$|`\mathrlap{\,/}{=}`|
|\mathring|$\mathring{a}$|`\mathring{a}`|
|\mathrm|$\mathrm{AaBb123}$|`\mathrm{AaBb123}`|
|\mathscr|$\mathscr{AB}$|`\mathscr{AaBb123}`<br>KaTeX supports A-Z|
|\mathsf|$\mathsf{AaBb123}$|`\mathsf{AaBb123}`|
|\mathsterling|$\mathsterling$||
|\mathstrut|$\sqrt{\mathstrut a}$|`\sqrt{\mathstrut a}`|
|\mathtip|<span style="color:firebrick;">Not supported</span>||
|\mathtt|$\mathtt{AaBb123}$|`\mathtt{AaBb123}`|
|\matrix|<span style="color:firebrick;">Not supported</span>|See `{matrix}`|
|{matrix}|$\begin{matrix}a&b\\c&d\end{matrix}$|`\begin{matrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{matrix}`|
|{matrix*}|$\begin{matrix*}[r]0&-1\\-1&0\end{matrix*}$|`\begin{matrix*}[r]`<br>&nbsp;&nbsp;&nbsp;`0 & -1 \\`<br>&nbsp;&nbsp;&nbsp;`-1 & 0`<br>`\end{matrix*}`|
|\max|$\max$||
|\mbox|<span style="color:firebrick;">Not supported</span>||
|\md|<span style="color:firebrick;">Not supported</span>||
|\mdseries|<span style="color:firebrick;">Not supported</span>||
|\measuredangle|$\measuredangle$||
|\medspace|$a\medspace b$|`a\medspace b`|
|\mho|$\mho$||
|\mid|$\{x∈ℝ\mid x>0\}$|`\{x∈ℝ\mid x>0\}`|
|\middle|$P\left(A\middle\vert B\right)$|`P\left(A\middle\vert B\right)`|
|\min|$\min$||
|\minuscolon|$\minuscolon$||
|\minuscoloncolon|$\minuscoloncolon$||
|\minuso|$\minuso$||
|\mit|<span style="color:firebrick;">Not supported</span>|See `\mathit`|
|\mkern|$a\mkern18mu b$|`a\mkern18mu b`|
|\mmlToken|<span style="color:firebrick;">Not supported</span>||
|\mod|$3\equiv 5 \mod 2$|`3\equiv 5 \mod 2`|
|\models|$\models$||
|\moveleft|<span style="color:firebrick;">Not supported</span>||
|\moveright|<span style="color:firebrick;">Not supported</span>||
|\mp|$\mp$||
|\mskip|$a\mskip{10mu}b$|`a\mskip{10mu}b`|
|\mspace|<span style="color:firebrick;">Not supported</span>||
|\Mu|$\Mu$||
|\mu|$\mu$||
|\multicolumn|<span style="color:firebrick;">Not supported</span>|[Issue #269](https://github.com/KaTeX/KaTeX/issues/269)|
|{multiline}|<span style="color:firebrick;">Not supported</span>||
|\multimap|$\multimap$||

## N

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\N|$\N$||
|\nabla|$\nabla$||
|\natnums|$\natnums$||
|\natural|$\natural$||
|\negmedspace|$a\negmedspace b$|`a\negmedspace b`|
|\ncong|$\ncong$||
|\ne|$\ne$||
|\nearrow|$\nearrow$||
|\neg|$\neg$||
|\negthickspace|$a\negthickspace b$|`a\negthickspace b`|
|\negthinspace|$a\negthinspace b$|`a\negthinspace b`|
|\neq|$\neq$||
|\newcommand|$\newcommand\chk{\checkmark} \chk$|`\newcommand\chk{\checkmark} \chk`|
|\newenvironment|<span style="color:firebrick;">Not supported</span>|[Issue #37](https://github.com/KaTeX/KaTeX/issues/37)|
|\Newextarrow|<span style="color:firebrick;">Not supported</span>||
|\newline|$a\newline b$|`a\newline b`|
|\nexists|$\nexists$||
|\ngeq|$\ngeq$||
|\ngeqq|$\ngeqq$||
|\ngeqslant|$\ngeqslant$||
|\ngtr|$\ngtr$||
|\ni|$\ni$||
|\nleftarrow|$\nleftarrow$||
|\nLeftarrow|$\nLeftarrow$||
|\nLeftrightarrow|$\nLeftrightarrow$||
|\nleftrightarrow|$\nleftrightarrow$||
|\nleq|$\nleq$||
|\nleqq|$\nleqq$||
|\nleqslant|$\nleqslant$||
|\nless|$\nless$||
|\nmid|$\nmid$||
|\nobreak|||
|\nobreakspace|$a\nobreakspace b$|`a\nobreakspace b`|
|\noexpand|||
|\nolimits|$\lim\nolimits_x$|`\lim\nolimits_x`|
|\nonumber|$$\begin{align}a&=b+c\nonumber\\d+e&=f\end{align}$$|`\begin{align}`<br>&nbsp;&nbsp;&nbsp;`a&=b+c \nonumber\\`<br>&nbsp;&nbsp;&nbsp;`d+e&=f`<br>`\end{align}`|
|\normalfont|<span style="color:firebrick;">Not supported</span>||
|\normalsize|$\normalsize normalsize$|`\normalsize normalsize`|
|\not|$\not =$|`\not =`|
|\notag|$$\begin{align}a&=b+c\notag\\d+e&=f\end{align}$$|`\begin{align}`<br>&nbsp;&nbsp;&nbsp;`a&=b+c \notag\\`<br>&nbsp;&nbsp;&nbsp;`d+e&=f`<br>`\end{align}`|
|\notin|$\notin$||
|\notni|$\notni$||
|\nparallel|$\nparallel$||
|\nprec|$\nprec$||
|\npreceq|$\npreceq$||
|\nRightarrow|$\nRightarrow$||
|\nrightarrow|$\nrightarrow$||
|\nshortmid|$\nshortmid$||
|\nshortparallel|$\nshortparallel$||
|\nsim|$\nsim$||
|\nsubseteq|$\nsubseteq$||
|\nsubseteqq|$\nsubseteqq$||
|\nsucc|$\nsucc$||
|\nsucceq|$\nsucceq$||
|\nsupseteq|$\nsupseteq$||
|\nsupseteqq|$\nsupseteqq$||
|\ntriangleleft|$\ntriangleleft$||
|\ntrianglelefteq|$\ntrianglelefteq$||
|\ntriangleright|$\ntriangleright$||
|\ntrianglerighteq|$\ntrianglerighteq$||
|\Nu|$\Nu$||
|\nu|$\nu$||
|\nVDash|$\nVDash$||
|\nVdash|$\nVdash$||
|\nvDash|$\nvDash$||
|\nvdash|$\nvdash$||
|\nwarrow|$\nwarrow$||

## O

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\O|$\text{\O}$|`\text{\O}`|
|\o|$\text{\o}$|`\text{\o}`|
|\odot|$\odot$||
|\OE|$\text{\OE}$|`\text{\OE}`|
|\oe|$\text{\oe}$|`\text{\oe}`|
|\officialeuro|<span style="color:firebrick;">Not supported</span>||
|\oiiint|$\oiiint$||
|\oiint|$\oiint$||
|\oint|$\oint$||
|\oldstyle|<span style="color:firebrick;">Not supported</span>||
|\omega|$\omega$||
|\Omega|$\Omega$||
|\Omicron|$\Omicron$||
|\omicron|$\omicron$||
|\ominus|$\ominus$||
|\operatorname|$\operatorname{asin} x$|`\operatorname{asin} x`|
|\operatorname\*|$\operatorname*{asin}\limits_y x$|`\operatorname*{asin}\limits_y x`|
|\operatornamewithlimits|$\operatornamewithlimits{asin}\limits_y x$|`\operatornamewithlimits{asin}\limits_y x`|
|\oplus|$\oplus$||
|\or|<span style="color:firebrick;">Not supported</span>||
|\origof|$\origof$||
|\oslash|$\oslash$||
|\otimes|$\otimes$||
|\over|${a+1 \over b+2}+c$|`{a+1 \over b+2}+c`|
|\overbrace|$\overbrace{x+⋯+x}^{n\text{ times}}$|`\overbrace{x+⋯+x}^{n\text{ times}}`|
|\overbracket|<span style="color:firebrick;">Not supported</span>||
|\overgroup|$\overgroup{AB}$|`\overgroup{AB}`|
|\overleftarrow|$\overleftarrow{AB}$|`\overleftarrow{AB}`|
|\overleftharpoon|$\overleftharpoon{AB}$|`\overleftharpoon{AB}`|
|\overleftrightarrow|$\overleftrightarrow{AB}$|`\overleftrightarrow{AB}`|
|\overline|$\overline{\text{a long argument}}$|`\overline{\text{a long argument}}`|
|\overlinesegment|$\overlinesegment{AB}$|`\overlinesegment{AB}`|
|\overparen|<span style="color:firebrick;">Not supported</span>|See `\overgroup`|
|\Overrightarrow|$\Overrightarrow{AB}$|`\Overrightarrow{AB}`|
|\overrightarrow|$\overrightarrow{AB}$|`\overrightarrow{AB}`|
|\overrightharpoon|$\overrightharpoon{ac}$|`\overrightharpoon{ac}`|
|\overset|$\overset{!}{=}$|`\overset{!}{=}`|
|\overwithdelims|<span style="color:firebrick;">Not supported</span>||
|\owns|$\owns$||

## P

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\P|$\text{\P}$|`\text{\P}`|
|\pagecolor|<span style="color:firebrick;">Not supported</span>|[Deprecated](https://en.wikipedia.org/wiki/Help:Displaying_a_formula#Deprecated_syntax)|
|\parallel|$\parallel$||
|\part|<span style="color:firebrick;">Not supported</span>|[Deprecated](https://en.wikipedia.org/wiki/Help:Displaying_a_formula#Deprecated_syntax)|
|\partial|$\partial$||
|\perp|$\perp$||
|\phantom|$\Gamma^{\phantom{i}j}_{i\phantom{j}k}$|`\Gamma^{\phantom{i}j}_{i\phantom{j}k}`|
|\phase|$\phase{-78^\circ}$|`\phase{-78^\circ}`|
|\Phi|$\Phi$||
|\phi|$\phi$||
|\Pi|$\Pi$||
|\pi|$\pi$||
|{picture}|<span style="color:firebrick;">Not supported</span>||
|\pitchfork|$\pitchfork$||
|\plim|$\plim$||
|\plusmn|$\plusmn$||
|\pm|$\pm$||
|\pmatrix|<span style="color:firebrick;">Not supported</span>|See `{pmatrix}`|
|{pmatrix}|$\begin{pmatrix}a&b\\c&d\end{pmatrix}$|`\begin{pmatrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{pmatrix}`
|{pmatrix*}|$\begin{pmatrix*}[r]0&-1\\-1&0\end{pmatrix*}$|`\begin{pmatrix*}[r]`<br>&nbsp;&nbsp;&nbsp;`0 & -1 \\`<br>&nbsp;&nbsp;&nbsp;`-1 & 0`<br>`\end{pmatrix*}`|
|\pmb|$\pmb{\mu}$|`\pmb{\mu}`|
|\pmod|$x\pmod a$|`x\pmod a`|
|\pod|$x \pod a$|`x \pod a`|
|\pounds|$\pounds$||
|\Pr|$\Pr$||
|\prec|$\prec$||
|\precapprox|$\precapprox$||
|\preccurlyeq|$\preccurlyeq$||
|\preceq|$\preceq$||
|\precnapprox|$\precnapprox$||
|\precneqq|$\precneqq$||
|\precnsim|$\precnsim$||
|\precsim|$\precsim$||
|\prime|$\prime$||
|\prod|$\prod$||
|\projlim|$\projlim$|`\projlim`|
|\propto|$\propto$||
|\providecommand|$\providecommand\greet{\text{Hello}} \greet$|`\providecommand\greet{\text{Hello}} \greet`|
|\psi|$\psi$||
|\Psi|$\Psi$||
|\pu |${123~\mathchoice{\textstyle\frac{\mathrm{kJ}}{\mathrm{mol}}}{\frac{\mathrm{kJ}}{\mathrm{mol}}}{\frac{\mathrm{kJ}}{\mathrm{mol}}}{\frac{\mathrm{kJ}}{\mathrm{mol}}}}$|`\pu{123 kJ//mol}` Requires an [extension](https://github.com/KaTeX/KaTeX/tree/main/contrib/mhchem/)|

## QR

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\Q|<span style="color:firebrick;">Not supported</span>|See `\Bbb{Q}`|
|\qquad|$a\qquad\qquad{b}$|`a\qquad\qquad{b}`|
|\quad|$a\quad\quad{b}$|`a\quad\quad{b}`|
|\R|$\R$||
|\r|$\text{\r{a}}$|`\text{\r{a}}`|
|\raise|<span style="color:firebrick;">Not supported</span>|see `\raisebox`|
|\raisebox|$h\raisebox{2pt}{ighe}r$|`h\raisebox{2pt}{$ighe$}r`|
|\rang|$\langle A\rang$|`\langle A\rang`|
|\rangle|$\langle A\rangle$|`\langle A\rangle`|
|\Rarr|$\Rarr$||
|\rArr|$\rArr$||
|\rarr|$\rarr$||
|\ratio|$\ratio$||
|\rBrace|$\rBrace$||
|\rbrace|$\rbrace$||
|\rbrack|$\rbrack$||
|{rcases}|$\begin{rcases}a&\text{if }b\\c&\text{if }d\end{rcases}$|`\begin{rcases}`<br>&nbsp;&nbsp;&nbsp;`a &\text{if } b  \\`<br>&nbsp;&nbsp;&nbsp;`c &\text{if } d`<br>`\end{rcases}`|
|\rceil|$\rceil$||
|\Re|$\Re$||
|\real|$\real$||
|\Reals|$\Reals$||
|\reals|$\reals$||
|\ref|<span style="color:firebrick;">Not supported</span>|[Issue #350](https://github.com/KaTeX/KaTeX/issues/350)|
|\relax|||
|\renewcommand|$\def\hail{Hi!}\renewcommand\hail{\text{Ahoy!}} \hail$|`\def\hail{Hi!}`<br>`\renewcommand\hail{\text{Ahoy!}}`<br>`\hail`|
|\renewenvironment|<span style="color:firebrick;">Not supported</span>||
|\require|<span style="color:firebrick;">Not supported</span>||
|\restriction|$\restriction$||
|\rfloor|$\rfloor$||
|\rgroup|$\rgroup$||
|\rhd|$\rhd$||
|\Rho|$\Rho$||
|\rho|$\rho$||
|\right|$\left.\dfrac a b\right)$|`\left.\dfrac a b\right)`|
|\Rightarrow|$\Rightarrow$||
|\rightarrow|$\rightarrow$||
|\rightarrowtail|$\rightarrowtail$||
|\rightharpoondown|$\rightharpoondown$||
|\rightharpoonup|$\rightharpoonup$||
|\rightleftarrows|$\rightleftarrows$||
|\rightleftharpoons|$\rightleftharpoons$||
|\rightrightarrows|$\rightrightarrows$||
|\rightsquigarrow|$\rightsquigarrow$||
|\rightthreetimes|$\rightthreetimes$||
|\risingdotseq|$\risingdotseq$||
|\rlap|$\rlap{\,/}{=}$|`\rlap{\,/}{=}`|
|\rm|$\rm AaBb12$|`\rm AaBb12`|
|\rmoustache|$\rmoustache$||
|\root|<span style="color:firebrick;">Not supported</span>||
|\rotatebox|<span style="color:firebrick;">Not supported</span>|[Issue #681](https://github.com/KaTeX/KaTeX/issues/681)|
|\rparen|$\rparen$||
|\rq|$\rq$||
|\rrbracket|$\rrbracket$||
|\Rrightarrow|$\Rrightarrow$||
|\Rsh|$\Rsh$||
|\rtimes|$\rtimes$||
|\Rule|<span style="color:firebrick;">Not supported</span>|see `\rule`
|\rule|$x\rule[6pt]{2ex}{1ex}x$|`x\rule[6pt]{2ex}{1ex}x`|
|\rVert|$\rVert$||
|\rvert|$\rvert$||

## S

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\S|$\text{\S}$|`\text{\S}`|
|\Sampi|<span style="color:firebrick;">Not supported</span>||
|\sampi|<span style="color:firebrick;">Not supported</span>||
|\sc|<span style="color:firebrick;">Not supported</span>|[Issue #471](https://github.com/KaTeX/KaTeX/issues/471)|
|\scalebox|<span style="color:firebrick;">Not supported</span>||
|\scr|<span style="color:firebrick;">Not supported</span>|See `\mathscr`|
|\scriptscriptstyle|$\scriptscriptstyle \frac cd$|`\scriptscriptstyle \frac cd`|
|\scriptsize|$\scriptsize scriptsize$|`\scriptsize scriptsize`|
|\scriptstyle|$\frac ab + {\scriptstyle \frac cd}$|`\frac ab + {\scriptstyle \frac cd}`|
|\sdot|$\sdot$||
|\searrow|$\searrow$||
|\sec|$\sec$||
|\sect|$\text{\sect}$|`\text{\sect}`|
|\set|$\set{x\VERT x<5}$|<code>\set{x&#124;x<5}</code> |
|\Set|$\Set{ x \VERT x<\frac 1 2 }$ | <code>\Set{ x &#124; x<\frac 1 2}</code> |
|\setlength|<span style="color:firebrick;">Not supported</span>|[Issue #687](https://github.com/KaTeX/KaTeX/issues/687)|
|\setminus|$\setminus$||
|\sf|$\sf AaBb123$|`\sf AaBb123`|
|\sharp|$\sharp$||
|\shortmid|$\shortmid$||
|\shortparallel|$\shortparallel$||
|\shoveleft|<span style="color:firebrick;">Not supported</span>||
|\shoveright|<span style="color:firebrick;">Not supported</span>||
|\sideset|<span style="color:firebrick;">Not supported</span>||
|\Sigma|$\Sigma$||
|\sigma|$\sigma$||
|\sim|$\sim$||
|\simcolon|$\simcolon$||
|\simcoloncolon|$\simcoloncolon$||
|\simeq|$\simeq$||
|\sin|$\sin$||
|\sinh|$\sinh$||
|\sixptsize|$\sixptsize sixptsize$|`\sixptsize sixptsize`|
|\sh|$\sh$||
|\skew|<span style="color:firebrick;">Not supported</span>||
|\skip|<span style="color:firebrick;">Not supported</span>||
|\sl|<span style="color:firebrick;">Not supported</span>||
|\small|$\small small$|`\small small`|
|\smallfrown|$\smallfrown$||
|\smallint|$\smallint$||
|{smallmatrix}|$\begin{smallmatrix} a & b \\ c & d \end{smallmatrix}$|`\begin{smallmatrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{smallmatrix}`|
|\smallsetminus|$\smallsetminus$||
|\smallsmile|$\smallsmile$||
|\smash|$\left(x^{\smash{2}}\right)$|`\left(x^{\smash{2}}\right)`|
|\smile|$\smile$||
|\smiley|<span style="color:firebrick;">Not supported</span>||
|\sout|$\sout{abc}$|`\sout{abc}`|
|\Space|<span style="color:firebrick;">Not supported</span>|see `\space`
|\space|$a\space b$|`a\space b`|
|\spades|$\spades$||
|\spadesuit|$\spadesuit$||
|\sphericalangle|$\sphericalangle$||
|{split}|$$\begin{equation}\begin{split}a &=b+c\\&=e+f\end{split}\end{equation}$$|`\begin{equation}`<br>`\begin{split}`<br>&nbsp;&nbsp;&nbsp;`a &=b+c\\`<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`&=e+f`<br>`\end{split}`<br>`\end{equation}`|
|\sqcap|$\sqcap$||
|\sqcup|$\sqcup$||
|\square|$\square$||
|\sqrt|$\sqrt[3]{x}$|`\sqrt[3]{x}`|
|\sqsubset|$\sqsubset$||
|\sqsubseteq|$\sqsubseteq$||
|\sqsupset|$\sqsupset$||
|\sqsupseteq|$\sqsupseteq$||
|\ss|$\text{\ss}$|`\text{\ss}`|
|\stackrel|$\stackrel{!}{=}$|`\stackrel{!}{=}`|
|\star|$\star$||
|\Stigma|<span style="color:firebrick;">Not supported</span>||
|\stigma|<span style="color:firebrick;">Not supported</span>||
|\strut|<span style="color:firebrick;">Not supported</span>||
|\style|<span style="color:firebrick;">Not supported</span>|Non standard|
|\sub|$\sub$||
|{subarray}|<span style="color:firebrick;">Not supported</span>||
|\sube|$\sube$||
|\Subset|$\Subset$||
|\subset|$\subset$||
|\subseteq|$\subseteq$||
|\subseteqq|$\subseteqq$||
|\subsetneq|$\subsetneq$||
|\subsetneqq|$\subsetneqq$||
|\substack|$$\sum_{\substack{0<i<m\\0<j<n}}$$|`\sum_{\substack{0<i<m\\0<j<n}}`|
|\succ|$\succ$||
|\succapprox|$\succapprox$||
|\succcurlyeq|$\succcurlyeq$||
|\succeq|$\succeq$||
|\succnapprox|$\succnapprox$||
|\succneqq|$\succneqq$||
|\succnsim|$\succnsim$||
|\succsim|$\succsim$||
|\sum|$\sum$||
|\sup|$\sup$||
|\supe|$\supe$||
|\Supset|$\Supset$||
|\supset|$\supset$||
|\supseteq|$\supseteq$||
|\supseteqq|$\supseteqq$||
|\supsetneq|$\supsetneq$||
|\supsetneqq|$\supsetneqq$||
|\surd|$\surd$||
|\swarrow|$\swarrow$||

## T

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\tag|$$\tag{3.1c} a^2+b^2=c^2$$|`\tag{3.1c} a^2+b^2=c^2`|
|\tag*|$$\tag*{3.1c} a^2+b^2=c^2$$|`\tag*{3.1c} a^2+b^2=c^2`|
|\tan|$\tan$||
|\tanh|$\tanh$||
|\Tau|$\Tau$||
|\tau|$\tau$||
|\tbinom|$\tbinom n k$|`\tbinom n k`|
|\TeX|$\TeX$||
|\text|$\text{ yes }\&\text{ no }$|`\text{ yes }\&\text{ no }`|
|\textasciitilde|$\text{\textasciitilde}$|`\text{\textasciitilde}`|
|\textasciicircum|$\text{\textasciicircum}$|`\text{\textasciicircum}`|
|\textbackslash|$\text{\textbackslash}$|`\text{\textbackslash}`|
|\textbar|$\text{\textbar}$|`\text{\textbar}`|
|\textbardbl|$\text{\textbardbl}$|`\text{\textbardbl}`|
|\textbf|$\textbf{AaBb123}$|`\textbf{AaBb123}`|
|\textbraceleft|$\text{\textbraceleft}$|`\text{\textbraceleft}`|
|\textbraceright|$\text{\textbraceright}$|`\text{\textbraceright}`|
|\textcircled|$\text{\textcircled a}$|`\text{\textcircled a}`|
|\textcolor|$\textcolor{blue}{F=ma}$|`\textcolor{blue}{F=ma}`|
|\textdagger|$\text{\textdagger}$|`\text{\textdagger}`|
|\textdaggerdbl|$\text{\textdaggerdbl}$|`\text{\textdaggerdbl}`|
|\textdegree|$\text{\textdegree}$|`\text{\textdegree}`|
|\textdollar|$\text{\textdollar}$|`\text{\textdollar}`|
|\textellipsis|$\text{\textellipsis}$|`\text{\textellipsis}`|
|\textemdash|$\text{\textemdash}$|`\text{\textemdash}`|
|\textendash|$\text{\textendash}$|`\text{\textendash}`|
|\textgreater|$\text{\textgreater}$|`\text{\textgreater}`|
|\textit|$\textit{AaBb}$|`\textit{AaBb}`|
|\textless|$\text{\textless}$|`\text{\textless}`|
|\textmd|$\textmd{AaBb123}$|`\textmd{AaBb123}`|
|\textnormal|$\textnormal{AB}$|`\textnormal{AB}`|
|\textquotedblleft|$\text{\textquotedblleft}$|`\text{\textquotedblleft}`|
|\textquotedblright|$\text{\textquotedblright}$|`\text{\textquotedblright}`|
|\textquoteleft|$\text{\textquoteleft}$|`\text{\textquoteleft}`|
|\textquoteright|$\text{\textquoteright}$|`\text{\textquoteright}`|
|\textregistered|$\text{\textregistered}$|`\text{\textregistered}`|
|\textrm|$\textrm{AaBb123}$|`\textrm{AaBb123}`|
|\textsc|<span style="color:firebrick;">Not supported</span>|[Issue #471](https://github.com/KaTeX/KaTeX/issues/471)|
|\textsf|$\textsf{AaBb123}$|`\textsf{AaBb123}`|
|\textsl|<span style="color:firebrick;">Not supported</span>||
|\textsterling|$\text{\textsterling}$|`\text{\textsterling}`|
|\textstyle|$\textstyle\sum_0^n$|`\textstyle\sum_0^n`|
|\texttip|<span style="color:firebrick;">Not supported</span>||
|\texttt|$\texttt{AaBb123}$|`\texttt{AaBb123}`|
|\textunderscore|$\text{\textunderscore}$|`\text{\textunderscore}`|
|\textup|$\textup{AaBb123}$|`\textup{AaBb123}`|
|\textvisiblespace|<span style="color:firebrick;">Not supported</span>||
|\tfrac|$\tfrac ab$|`\tfrac ab`|
|\tg|$\tg$||
|\th|$\th$||
|\therefore|$\therefore$||
|\Theta|$\Theta$||
|\theta|$\theta$||
|\thetasym|$\thetasym$||
|\thickapprox|$\thickapprox$||
|\thicksim|$\thicksim$||
|\thickspace|$a\thickspace b$|`a\thickspace b`|
|\thinspace|$a\thinspace b$|`a\thinspace b`|
|\tilde|$\tilde M$|`\tilde M`|
|\times|$\times$||
|\Tiny|<span style="color:firebrick;">Not supported</span>|see `\tiny`|
|\tiny|$\tiny tiny$|`\tiny tiny`|
|\to|$\to$||
|\toggle|<span style="color:firebrick;">Not supported</span>||
|\top|$\top$||
|\triangle|$\triangle$||
|\triangledown|$\triangledown$||
|\triangleleft|$\triangleleft$||
|\trianglelefteq|$\trianglelefteq$||
|\triangleq|$\triangleq$||
|\triangleright|$\triangleright$||
|\trianglerighteq|$\trianglerighteq$||
|\tt|${\tt AaBb123}$|`{\tt AaBb123}`|
|\twoheadleftarrow|$\twoheadleftarrow$||
|\twoheadrightarrow|$\twoheadrightarrow$||

## U

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\u|$\text{\u{a}}$|`\text{\u{a}}`|
|\Uarr|$\Uarr$||
|\uArr|$\uArr$||
|\uarr|$\uarr$||
|\ulcorner|$\ulcorner$||
|\underbar|$\underbar{X}$|`\underbar{X}`|
|\underbrace|$\underbrace{x+⋯+x}_{n\text{ times}}$|`\underbrace{x+⋯+x}_{n\text{ times}}`|
|\underbracket|<span style="color:firebrick;">Not supported</span>||
|\undergroup|$\undergroup{AB}$|`\undergroup{AB}`|
|\underleftarrow|$\underleftarrow{AB}$|`\underleftarrow{AB}`|
|\underleftrightarrow|$\underleftrightarrow{AB}$|`\underleftrightarrow{AB}`|
|\underrightarrow|$\underrightarrow{AB}$|`\underrightarrow{AB}`|
|\underline|$\underline{\text{a long argument}}$|`\underline{\text{a long argument}}`|
|\underlinesegment|$\underlinesegment{AB}$|`\underlinesegment{AB}`|
|\underparen|<span style="color:firebrick;">Not supported</span>|See `\undergroup`|
|\underrightarrow|$\underrightarrow{AB}$|`\underrightarrow{AB}`|
|\underset|$\underset{!}{=}$|`\underset{!}{=}`|
|\unicode|<span style="color:firebrick;">Not supported</span>||
|\unlhd|$\unlhd$||
|\unrhd|$\unrhd$||
|\up|<span style="color:firebrick;">Not supported</span>||
|\Uparrow|$\Uparrow$||
|\uparrow|$\uparrow$||
|\Updownarrow|$\Updownarrow$||
|\updownarrow|$\updownarrow$||
|\upharpoonleft|$\upharpoonleft$||
|\upharpoonright|$\upharpoonright$||
|\uplus|$\uplus$||
|\uproot|<span style="color:firebrick;">Not supported</span>||
|\upshape|<span style="color:firebrick;">Not supported</span>||
|\Upsilon|$\Upsilon$||
|\upsilon|$\upsilon$||
|\upuparrows|$\upuparrows$||
|\urcorner|$\urcorner$||
|\url|$\footnotesize\url{https://katex.org/}$|`\url{https://katex.org/}` Requires `trust` [option](options.md)|
|\utilde|$\utilde{AB}$|`\utilde{AB}`|

## V

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\v|$\text{\v{a}}$|`\text{\v{a}}`|
|\varcoppa|<span style="color:firebrick;">Not supported</span>||
|\varDelta|$\varDelta$||
|\varepsilon|$\varepsilon$||
|\varGamma|$\varGamma$||
|\varinjlim|$\varinjlim$|`\varinjlim`|
|\varkappa|$\varkappa$||
|\varLambda|$\varLambda$||
|\varliminf|$\varliminf$|`\varliminf`|
|\varlimsup|$\varlimsup$|`\varlimsup`|
|\varnothing|$\varnothing$||
|\varOmega|$\varOmega$||
|\varPhi|$\varPhi$||
|\varphi|$\varphi$||
|\varPi|$\varPi$||
|\varpi|$\varpi$||
|\varprojlim|$\varprojlim$|`\varprojlim`|
|\varpropto|$\varpropto$||
|\varPsi|$\varPsi$||
|\varrho|$\varrho$||
|\varSigma|$\varSigma$||
|\varsigma|$\varsigma$||
|\varstigma|<span style="color:firebrick;">Not supported</span>||
|\varsubsetneq|$\varsubsetneq$||
|\varsubsetneqq|$\varsubsetneqq$||
|\varsupsetneq|$\varsupsetneq$||
|\varsupsetneqq|$\varsupsetneqq$||
|\varTheta|$\varTheta$||
|\vartheta|$\vartheta$||
|\vartriangle|$\vartriangle$||
|\vartriangleleft|$\vartriangleleft$||
|\vartriangleright|$\vartriangleright$||
|\varUpsilon|$\varUpsilon$||
|\varXi|$\varXi$||
|\vcentcolon|$\mathrel{\vcentcolon =}$|`\mathrel{\vcentcolon =}`|
|\vcenter|$a+\left(\vcenter{\frac{\frac a b}c}\right)$|`a+\left(\vcenter{\hbox{$\frac{\frac a b}c$}}\right)`<br>TeX (strict) syntax|
|\vcenter|$a+\left(\vcenter{\frac{\frac a b}c}\right)$|`a+\left(\vcenter{\frac{\frac a b}c}\right)`<br>non-strict syntax|
|\Vdash|$\Vdash$||
|\vDash|$\vDash$||
|\vdash|$\vdash$||
|\vdots|$\vdots$||
|\vec|$\vec{F}$|`\vec{F}`|
|\vee|$\vee$||
|\veebar|$\veebar$||
|\verb|$\verb!\frac a b!$|`\verb!\frac a b!`|
|\Vert|$\Vert$||
|\vert|$\vert$||
|\vfil|<span style="color:firebrick;">Not supported</span>||
|\vfill|<span style="color:firebrick;">Not supported</span>||
|\vline|<span style="color:firebrick;">Not supported</span>|[Issue #269](https://github.com/KaTeX/KaTeX/issues/269)|
|{Vmatrix}|$\begin{Vmatrix}a&b\\c&d\end{Vmatrix}$|`\begin{Vmatrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{Vmatrix}`|
|{Vmatrix*}|$\begin{Vmatrix*}[r]0&-1\\-1&0\end{Vmatrix*}$|`\begin{Vmatrix*}[r]`<br>&nbsp;&nbsp;&nbsp;`0 & -1 \\`<br>&nbsp;&nbsp;&nbsp;`-1 & 0`<br>`\end{Vmatrix*}`|
|{vmatrix}|$\begin{vmatrix}a&b\\c&d\end{vmatrix}$|`\begin{vmatrix}`<br>&nbsp;&nbsp;&nbsp;`a & b \\`<br>&nbsp;&nbsp;&nbsp;`c & d`<br>`\end{vmatrix}`|
|{vmatrix*}|$\begin{vmatrix*}[r]0&-1\\-1&0\end{vmatrix*}$|`\begin{vmatrix*}[r]`<br>&nbsp;&nbsp;&nbsp;`0 & -1 \\`<br>&nbsp;&nbsp;&nbsp;`-1 & 0`<br>`\end{vmatrix*}`|
|\vphantom|$\overline{\vphantom{M}a}$|`\overline{\vphantom{M}a}`|
|\Vvdash|$\Vvdash$||

## W

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\wedge|$\wedge$||
|\weierp|$\weierp$||
|\widecheck|$\widecheck{AB}$|`\widecheck{AB}`|
|\widehat|$\widehat{AB}$|`\widehat{AB}`|
|\wideparen|<span style="color:firebrick;">Not supported</span>|[Issue #560](https://github.com/KaTeX/KaTeX/issues/560)|
|\widetilde|$\widetilde{AB}$|`\widetilde{AB}`|
|\wp|$\wp$||
|\wr|$\wr$||

## X

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\xcancel|$\xcancel{ABC}$|`\xcancel{ABC}`|
|\xdef|$\def\foo{a}\xdef\fcopy{\foo}\def\foo{}\fcopy$|`\def\foo{a}\xdef\fcopy{\foo}\def\foo{}\fcopy`|
|\Xi|$\Xi$||
|\xi|$\xi$||
|\xhookleftarrow|$\xhookleftarrow{abc}$|`\xhookleftarrow{abc}`|
|\xhookrightarrow|$\xhookrightarrow{abc}$|`\xhookrightarrow{abc}`|
|\xLeftarrow|$\xLeftarrow{abc}$|`\xLeftarrow{abc}`|
|\xleftarrow|$\xleftarrow{abc}$|`\xleftarrow{abc}`|
|\xleftharpoondown|$\xleftharpoondown{abc}$|`\xleftharpoondown{abc}`|
|\xleftharpoonup|$\xleftharpoonup{abc}$|`\xleftharpoonup{abc}`|
|\xLeftrightarrow|$\xLeftrightarrow{abc}$|`\xLeftrightarrow{abc}`|
|\xleftrightarrow|$\xleftrightarrow{abc}$|`\xleftrightarrow{abc}`|
|\xleftrightharpoons|$\xleftrightharpoons{abc}$|`\xleftrightharpoons{abc}`|
|\xlongequal|$\xlongequal{abc}$|`\xlongequal{abc}`|
|\xmapsto|$\xmapsto{abc}$|`\xmapsto{abc}`|
|\xRightarrow|$\xRightarrow{abc}$|`\xRightarrow{abc}`|
|\xrightarrow|$\xrightarrow{abc}$|`\xrightarrow{abc}`|
|\xrightharpoondown|$\xrightharpoondown{abc}$|`\xrightharpoondown{abc}`|
|\xrightharpoonup|$\xrightharpoonup{abc}$|`\xrightharpoonup{abc}`|
|\xrightleftharpoons|$\xrightleftharpoons{abc}$|`\xrightleftharpoons{abc}`|
|\xtofrom|$\xtofrom{abc}$|`\xtofrom{abc}`|
|\xtwoheadleftarrow|$\xtwoheadleftarrow{abc}$|`\xtwoheadleftarrow{abc}`|
|\xtwoheadrightarrow|$\xtwoheadrightarrow{abc}$|`\xtwoheadrightarrow{abc}`|

## YZ

|Symbol/Function |  Rendered   | Source or Comment|
|:---------------|:------------|:-----------------|
|\yen|$\yen$||
|\Z|$\Z$||
|\Zeta|$\Zeta$||
|\zeta|$\zeta$||
