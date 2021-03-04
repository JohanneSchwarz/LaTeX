# LaTeX

Repo to parse LaTeX
Instructions see .gitlab-ci.yml


2 Pictures in "one row" 
    \usepackage{subfigure}
    %einbinden einer Grafik
    \begin{figure}
        \subfigure[Bezeichnung der linken Grafik]{\includegraphics[width=0.49\textwidth]{ordner/name1.jpg}}
        \subfigure[Bezeichnung der rechten Grafik]{\includegraphics[width=0.49\textwidth]{ordner/name2.jpg}}
        \caption{Titel unterm gesamten Bild}
    \end{figure}
