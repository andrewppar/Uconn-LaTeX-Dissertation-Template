# Uconn-LaTeX-Dissertation-Template
This is a template for formatting a dissertation in LaTeX according to the University of Connecticut's specifications

# Usage
Most of the directions are contained in the various files. Fill in the dissertation template and approval page template according to the comments. Once the approval page is built copy the .pdf to the main directory, the one containing main.tex. 

Put the individual chapters in the same directory as main.tex without compiling them. There is an example chatper included in this project called theoriesOfMeaning.tex. 

Because this template uses the standalone package the preamble that is required for compiling any chapter, if it were to be its own LaTeX document is put in the preamble for main. For example, if Chapter 6 requires the package tikz, do not put \usepackage{tikz} in the preamble of chapter-6.tex, but instead in the preamble of main.tex. 
