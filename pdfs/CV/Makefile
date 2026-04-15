all: latexmk

latexmk:
	latexmk -pdf -f bezbaruah_cv

todo:
	grep -R -s -n todo *.tex

clean:
	rm -f *.fls *.fdb_latexmk *.aux *.log *.dvi *.bbl *.blg *.ilg *.ind *.toc *.idx *.out *.nav *.snm *.thm *.synctex.gz
