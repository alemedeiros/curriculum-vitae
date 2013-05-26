.PHONY: all clean rebuild

all: cv-en.pdf

rebuild: clean all

%.pdf: %.tex
	pdflatex -interaction=nonstopmode $*
	pdflatex -interaction=nonstopmode $*
	pdflatex -interaction=nonstopmode $*

clean:
	-rm *.{aux,log,out,pdf}
