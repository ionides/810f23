# Supplement to Homework 12

## If your Latex distribution is missing `sty` files

* You can copy missing `sty` files into your working directory from the internet
.

* Better, you can get a more complete Latex distribution. On a Mac, if you install `Xcode`, `Xcode command line tools`, and `MacPorts` (all of which are good to have for scientific computing) you can open a terminal and run
```
sudo port install texlive-latex-extra
```

* If you do not have Latex on your laptop, and it is a UM Mac laptop, you can install MacTex via the Managed Software Center. Once this is installed, and your machine is restarted, then you can check that `pdflatex` is on the search path by typing in a terminal
```
which pdflatex
```

## If you have problems running the code in Rstudio

* Note that the homework does not ask you to use Rstudio. You can just run R in a terminal window.

* Using Rstudio sometimes introduces problems. This is fairly rare, but in this particular case it happened to several people that Rstudio behaved inappropriately with the Rnw file.

* In general, stripping away an unnecessary layer of code (here, Rstudio) is worth trying when debugging. 

## Installation of missing packages

* Most people will have to install missing R packages. The code needs at least the following packages:

```
ggplot2, knitr, doParallel, doRNG, fields, pomp, spatPomp
```
