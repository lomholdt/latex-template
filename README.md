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