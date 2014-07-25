
all: clean build display

clean:
	rm -rf bld
build:
	mkdir -p bld
	pdflatex -output-directory=bld index.tex
	pdflatex -output-directory=bld index.tex
	pdflatex -output-directory=bld index.tex
	pdflatex -output-directory=bld index.tex

display:
	evince bld/index.pdf
