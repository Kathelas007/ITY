NAME=proj5

all: $(NAME).tex
	latex $(NAME).tex
	bibtex $(NAME).aux
	latex $(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex
	dvips $(NAME).dvi
	ps2pdf $(NAME).ps

clean:
	rm $(NAME).aux $(NAME).log $(NAME).pdf $(NAME).dvi $(NAME).ps $(NAME).bbl $(NAME).blg $(NAME).nav $(NAME).out $(NAME).vrb $(NAME).toc $(NAME).snm
