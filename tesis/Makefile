all:	
	latex tesis-larevalo.tex
	bibtex tesis-larevalo
	makeindex -s tesis-larevalo.ist -t tesis-larevalo.glg -o tesis-larevalo.gls tesis-larevalo.glo
	makeindex -s tesis-larevalo.ist -t tesis-larevalo.alg -o tesis-larevalo.acr tesis-larevalo.acn
	latex tesis-larevalo.tex
	latex tesis-larevalo.tex
	dvipdf tesis-larevalo.dvi
	evince tesis-larevalo.pdf
	make clean
	
clean:	
	rm -f *.log
	rm -f *.aux
	rm -f *.dvi
	rm -f *.glg
	rm -f *.glo
	rm -f *.gls
	rm -f *.ist
	rm -f *.ntn
	rm -f *.out
	rm -f *.toc
	rm -f *.acn
	rm -f *.acr
	rm -f *.alg
	rm -f *.bbl
	rm -f *.blg	
	rm -f *.lof	
	rm -f *.lot	
	rm -f *.idx
