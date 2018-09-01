# listings-rust
A Rust language and style specification for the LaTeX-package listings

## Usage
* place the `listings-rust.sty` where `latex` can find it
* import `listings` and `listings-rust` in your LaTeX document with `\usepackage{listings, listings-rust}`
* select the language `Rust` in the `lstlistings` environment and specify all required keyword styles, e.g.
  ```latex
  \begin{lstlisting}[
    language=Rust,
    keywordstyle=[1]{\bfseries\color[rgb]{0,.3,.7}},
    keywordstyle=[2]{\bfseries\color{Orange}},
    keywordstyle=[3]{\bfseries\color{Coral}},
    keywordstyle=[4]{\bfseries\color{Teal}},
    keywordstyle=[5]{\color{SaddleBrown}},
    keywordstyle=[6]{\color{DodgerBlue!75!black}},
    keywordstyle=[7]{\color[rgb]{.0,.2,.41}},
  ]
  // your source code
  \end{lstlisting}
  ```
