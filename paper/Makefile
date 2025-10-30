TARGET=paper

all: pdf

pdf:
	latexmk -latexoption="-file-line-error -synctex=1" -pdf $(TARGET).tex

clean:
	latexmk -c

cleanall: clean
	latexmk -C
	rm -f paper.bbl
