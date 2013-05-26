.PHONY: all clean rebuild

all: cv-br.pdf

rebuild: clean all

%.pdf: %.tex
	pdflatex -interaction=nonstopmode $*
	pdflatex -interaction=nonstopmode $*
	pdflatex -interaction=nonstopmode $*

clean:
	-rm *.{aux,log,out,pdf}
