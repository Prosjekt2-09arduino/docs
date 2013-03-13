Building a LaTeX project.

All sections are located in /section/ and integrated in Rapport.tex with the line \input{section/<file_name>}.
Note that the <filename> do not need to include fileending (.tex). 

All \usepackage{} statements will be located in Rapport.tex, and this makes sure we don't use diffirent styles in each section.
What we need to do in each <section>.tex is write sections like we would in a smaller project. \section{}

Sections will not compile standing on their own, but the full report will compile if all sections integrated are written to compile.

Images:
	All images/screenshots will be located in /images/ ad integrated in the fitting section with the line \includegraphics[scale=<scale>]{images/<image_name>} . Here, <image_name> will include fileending (.png .pdf .whatever), since file type is not given in \includegraphics{}.


	Tips & Tricks in LaTeX? http://en.wikibooks.org/wiki/LaTeX/
