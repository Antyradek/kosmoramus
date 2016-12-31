INKSCAPE=inkscape
PDFS=crystal page1 page2 power devices chips weapons

all: $(PDFS) card.pdf

$(PDFS):
	$(INKSCAPE) -A $@.pdf $@.svg 

card.pdf: page1.pdf page2.pdf
	pdfunite page1.pdf page2.pdf card.pdf