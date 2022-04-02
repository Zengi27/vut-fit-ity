TARGET=proj3

$(TARGET): $(TARGET).tex
	latex $(TARGET).tex
	latex $(TARGET).tex
	dvips $(TARGET).dvi
	ps2pdf -sPAPERSIZE=a4 $(TARGET).ps
