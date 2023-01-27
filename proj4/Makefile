TARGET=proj4

$(TARGET): $(TARGET).tex
	latex $(TARGET).tex
	bibtex $(TARGET).aux
	latex $(TARGET).tex
	latex $(TARGET).tex
	dvips $(TARGET).dvi
	ps2pdf -sPAPERSIZE=a4 $(TARGET).ps
