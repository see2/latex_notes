# latex_notes
Notes of using latexes



## Use some Chinese in the document

```
% UTF-8 encoding
% bad-looking fonts (CJKfonts package)
% latex+dvips, latex+dvipdfm(x) or pdflatex
\documentclass{article}
\usepackage{CJKutf8}
\begin{document}
\begin{CJK*}{UTF8}{gbsn}
文章内容。
\clearpage\end{CJK*}
\end{document}
```
