# HyperTeX

HyperTeX is (intended to be) an HTML parser written entirely with LaTeX
macros. Why, you ask? Because it sounded like a good idea at the time.

The goal is to be able to write documents like this:

``` latex
% document.tex

\documentclass{article}

\begin{document}
\html{
<h1>Title</h1>
<p>Paragraph</p>
}
\end{document}
```
