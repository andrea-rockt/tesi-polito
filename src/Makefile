TARGET=main
TMPDIR=../tmp
OUTDIR=../out
PDFLATEX=pdflatex -output-directory=$(TMPDIR)
AFTERALL=postbuild
include Makefile.include

postbuild:
	mv $(TMPDIR)/*.pdf $(OUTDIR)
