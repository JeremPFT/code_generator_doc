HOME=D:/Users/jpiffret/AppData/Roaming
all:
	-[ -f *.aux ] && rm *.aux
	-[ -f *.log ] && rm *.log
	-[ -f *.out ] && rm *.out
	pdflatex --output-dir=${HOME}/tmp code_generator.tex
	mv ${HOME}/tmp/*pdf .
