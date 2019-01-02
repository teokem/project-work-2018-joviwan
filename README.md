# project-work-2018-joviwan

# BibTeX in Jupyter?

## What we need?
- A Jupyter file (.ipynb)
- A BibTeX file (.bib)
- A template file (.tplex)

## How to run? 
%%bash<br>
ipython nbconvert --to latex --template citations.tplx FN.ipynb<br>
pdflatex FN.tex<br>
bibtex FN<br>
pdflatex FN.tex<br>
