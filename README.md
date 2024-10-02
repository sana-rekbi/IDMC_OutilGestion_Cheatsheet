# IDMC_OutilGestion_Cheatsheet

## Description of command `git merge`

The `git merge` command incorporates changes from the named commits (since the time their histories diverged).  
Here are 3 common options for the command:
- `--commit`: Automatically creates a commit if no conflicts are present.
- `--no-commit`: Merges changes but does not automatically commit them.
- `--edit`: Opens an editor to modify the commit message.

An example of a command to list files would be: `ls -l`.

---

## Introduction to LaTeX

LaTeX is a document preparation system widely used for scientific, academic, and professional articles. It allows precise formatting, particularly for documents containing mathematics, bibliographic references, or figures.

## General structure of a LaTeX file

```latex
\documentclass{article}
\title{LaTeX Document Example}
\author{Author's Name}
\date{\today}

\begin{document}
\maketitle

\section{Introduction}
This is a simple example of a document written in LaTeX.

\section{Conclusion}
End of the example.

\end{document}

