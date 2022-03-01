TARGET=proj1

$(TARGET): %(TARGET).tex
	latex $(TARGET).tex
	latex $(TARGET).tex
	dvips -t a4 $(TARGET).dvi
	ps2pdf $(TARGET).ps

clean: 
	$(RM) $(TARGET)