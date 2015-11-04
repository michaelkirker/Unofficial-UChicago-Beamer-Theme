# Unofficial-UChicago-Beamer-Theme
Files to theme your LaTeX Beamer presentation to match the University of Chicago colors.

Note that this theme is unofficial. It is in no way endorsed by the University of Chicago.

## Contact details ##

Created by: Michael Kirker

Website: [http://michaelkirker.net](http://michaelkirker.net "http://michaelkirker.net")

Git repository: [https://github.com/michaelkirker/Unofficial-UChicago-Beamer-Theme]("https://github.com/mkirker/Unofficial-UChicago-Beamer-Theme")


## Repository structure ##

* /graphics/
	* Folder containing the graphical images used in the slides.
* beamerthemeUnofficialUChicago.sty
	* Beamer theme style file.
* Unofficial\_UChicago\_Theme\_Example.tex
	* Example Beamer presentation showing the main features of the theme.




## How to use the theme ##

Add the folder */graphics/* and the file *beamerthemeUnofficialUChicago.sty* to the folder containing the .tex file for your beamer presentation.

Alternatively, add the folder and .sty file to the TeX search path so that all your beamer presentations can call the files from one location. 


The following code illustrates how to call the theme inside your .tex file.

    \documentclass[12pt]{beamer}
	
	\usetheme{UnofficialUChicago}

	\begin{document}

	\maketitle % It is important to use the command "\maketitle" to generate your title slide. "\titlepage" does not automatically generate the background image.

	% The rest of your Beamer presentation goes here

	\end{document}



