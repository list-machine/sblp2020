default: pdf

pdf:
	lhs2TeX --agda paper.lagda > paper.tex
	pdflatex paper
	pdflatex paper
	bibtex paper
	pdflatex paper

clean:
	rm -rf paper.aux paper.bbl paper.blg paper.log paper.pdf paper.spl paper.tex
