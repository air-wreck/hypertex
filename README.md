# HyperTeX Markup Language

Ever wished you could write LaTeX as HTML? No? Well, now you can anyway!

``` latex
\documentclass{article}
\usepackage{hypertex}

\begin{document}
  \begin{html}
    <h1>Title</h1>
    <p>
      % Write HTML!
    </p>
  \end{html}
\end{document}
```

See `example.tex` and `example.pdf` for more. Essentially, this is a
very primitive HTML parser implemented in LaTeX macros.

To use, just download `hypertex.sty` and `\usepackage{hypertex}` in your
document. Then compile however you normally like to compile LaTeX.
