.PHONY: all clean view

all: main.pdf

main.pdf: main.tex
	pdflatex -interaction=nonstopmode main.tex
	pdflatex -interaction=nonstopmode main.tex
	pdflatex -interaction=nonstopmode main.tex

view: main.pdf
	xdg-open main.pdf 2>/dev/null || open main.pdf 2>/dev/null || true

clean:
	rm -f main.aux main.log main.out main.toc main.pdf main.bbl main.blg
