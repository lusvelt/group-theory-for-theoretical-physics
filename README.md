# Group theory for theoretical physics
This is a LaTeX project hich aims at collecting useful and common group theoretical tools which are used in theoretical physics, in a consistent and self-contained way.


### Development
It is suggested to use vscode with LaTeX Workshop extension for contributing to this project.
In the `.vscode` folder of this project, there are the settings that setup the recipe for compiling with `bibtex` and `pdflatex`.


### Lists
To write numbered lists (for example when listing properties of a mathematical objects, which have to be referenced later), use
```
\begin{enumerate}
    \item Property one \label{prop1}
    \item Property two \label{prop2}
\end{enumerate}
```

### Labels
To reference equations, use `\eqref{eq:myeq}`

### Environments
The following environments are defined:
- theorem
- definition
- proof
- example
- proposition
- lemma
- corollary
- remark
So, for example, one can use
```
\begin{remark}
    The above theorem does not imply that ...
\end{remark}
```

### Bibliography
`bibtex` is used, and references should be inserted in `references.bib`, and cited using `\cite{<reference_label>}`.
