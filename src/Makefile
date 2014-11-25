TARGET=main
TMPDIR=../tmp
OUTDIR=../out
PDFLATEX=pdflatex -output-directory=$(TMPDIR)
BIBTEX= cp -f main.bib ../tmp/;cd ../tmp; bibtex
AFTERALL=postbuild
include Makefile.include

postbuild:
	mv $(TMPDIR)/*.pdf $(OUTDIR)
