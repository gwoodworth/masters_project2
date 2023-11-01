PDF= pdflatex

thesis: main.tex
	$(PDF) main.tex
	bibtex main
	$(PDF) main.tex
	$(PDF) main.tex

once: main.tex
	$(PDF) main.tex

clean:
	rm *.log *.bbl *.blg *.aux *.toc *.lof
	
