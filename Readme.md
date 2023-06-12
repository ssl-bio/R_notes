# Notes on R for basic statistic analysis


## Description

Basic notes on statistical analysis on `R`


### Introduction to Categorical Data Analysis

Notes and exercises from 'Introduction to Categorical Data Analysis' by <a href="#citeproc_bib_item_1">Agresti 2007</a> Chapters 7-10

Notes and exercises are written in Sweave (`*.Rnw`) following the notes from <a href="#citeproc_bib_item_2">Thompson 2007</a>. These are meant to produce a `pdf` document with embedded `R` code (input and output).

Provided that `R` and a `LaTex` distribution are both available, along with the required packages, a pdf output can be produced using the following commands

```bash
# Example for Notes-CH7.Rnw
# results in *.tex file
R CMD Sweave Notes-CH7.Rnw

# results in a *.pdf file
arara Notes-Ch7.tex

# alternatively if arara is not available
# pdflatex --shell-escape Notes-Ch7.tex
# biber Notes-Ch7
# pdflatex --shell-escape Notes-Ch7.tex
```


# References
  <div class="csl-entry"><a id="citeproc_bib_item_1"></a>Agresti, Alan. 2007. <i>An Introduction to Categorical Data Analysis</i>. 2nd ed. Hoboken NJ: Wiley-Interscience.</div>
  <div class="csl-entry"><a id="citeproc_bib_item_2"></a>Thompson, Laura A. 2007. “S-plus (and R) Manual to Accompany Agresti’s ``Categorical Data Analysis’’ (2002).” <a href="https://users.stat.ufl.edu/~aa/cda/Thompson_manual.pdf">https://users.stat.ufl.edu/~aa/cda/Thompson_manual.pdf</a>.</div>
</div>
