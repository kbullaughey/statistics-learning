DOC = mixture
#BIB = allrefs.bib
#BIBSTYLE = plos2009.bst
#SUPPAGE1 = 35

all: $(DOC).pdf

$(DOC).pdf: $(DOC).tex 
	echo "Building PDF"
	echo "s" | pdflatex $(DOC).tex
	echo "s" | pdflatex $(DOC).tex > last.log

clean:
	-rm $(DOC).aux $(DOC).blg $(DOC).pdf $(DOC).log $(DOC).bbl $(BIB) $(DOC).supf $(DOC).supt $(DOC).suptl $(DOC).sup $(DOC).lot $(DOC).lof
