MAIN="main"

all:
	echo "Running pdflatex (1st run)..."
	pdflatex --shell-escape $(MAIN).tex
	echo "Running bibtex..."
	bibtex $(MAIN).aux
	echo "Running pdflatex (2nd run)... go figure..."
	pdflatex --shell-escape $(MAIN).tex
