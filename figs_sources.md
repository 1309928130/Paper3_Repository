# Supplementary Material 2 - Sources of Figures

Below is an example of the LaTeX code for the table of figure sources:

```latex
\section*{Supplementary Material 2 - Sources of figures}

\begin{xltabular}{\textwidth}{p{0.01\textwidth} p{0.42\textwidth} p{0.50\textwidth}} % adjust widths manually

    \caption{Sources of Figures} 
    \label{tab:figsources} \\
    
    \hline
    \textbf{N} & \textbf{Figure and Caption} & \textbf{Source} \\
    \hline
    \endfirsthead
    
    \caption{Sources of Figures (continued)} \\
    \hline
    \textbf{N} & \textbf{Figure and Caption} & \textbf{Source} \\
    \hline
    \endhead

