all: article.tex
	pdflatex article
	biber article
	pdflatex article

refs: refs.bib
	biber article

clean:
	rm *.aux *.bcf *.log *.run.xml *.bbl *.blg
