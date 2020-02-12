LATEX=lualatex
HOME=D:/Users/jpiffret/AppData/Roaming
all:
	-[ -f *.aux ] && rm *.aux
	-[ -f *.log ] && rm *.log
	-[ -f *.out ] && rm *.out
	$(LATEX) --output-dir=${HOME}/tmp node_minipage.tex
	mv ${HOME}/tmp/*pdf .
