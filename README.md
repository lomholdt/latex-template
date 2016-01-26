# LaTeX Standard Template
This is my standard LaTeX template, that includes all the initial setup that is often needed. It includes packages for APA Style citing, footnotes, images, hyperlinking within the PDF and more.

## Images
To add an image, insert the folowing code
```
\begin{figure}[H] % [H] to add figure directly where code is in text
\capstart
	\centering
		%\frame{\includegraphics[width=\textwidth]{myImage.jpg}}
        \missingfigure{Insert a picture here}
	\caption[My image caption in the TOC]{My image caption under the actual image \label{fig:my-label-for-the-image}}
\end{figure}
```

## Citation
For citing we use APA Style. The package is already included, so it's easy to cite by doing either of the following commands:
- `\cite{yourstone2008classroom}` to cite whole articles
- `\cite[p.~280]{yourstone2008classroom}` to cite a specific page of an author
- `\citeA{yourstone2008classroom}` to cite just the author