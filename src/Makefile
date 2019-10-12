All: tiles clean

tiles:
	./latexdockercmd.sh pdflatex city_tiles.tex
	./latexdockercmd.sh pdflatex spell_tiles.tex
	mv city_tiles.pdf ../
	mv spell_tiles.pdf ../

clean:
	rm *.log *.aux
