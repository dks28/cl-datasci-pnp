all: build clean

build: build1 biber build2

biber: 
	biber report

build1:
	xelatex report.tex
build2:
	xelatex report.tex
	xelatex report.tex

clean:
	rm *.log *.out *.aux *.bbl *.bcf *.blg *.xml
