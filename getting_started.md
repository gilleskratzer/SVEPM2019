
# Getting started checklist

In order to best profit from the workshop please follow the instruction below. R is a programming language that is especially powerful for data exploration, visualization, and statistical analysis. To interact with R, we recommend to use RStudio.

- Install [R](https://www.r-project.org/)
- Install [RStudio](https://www.rstudio.com/) (not mandatory but strongly recommended)
- Install [abn](https://cran.r-project.org/package=abn):
```
install.packages("abn")
```
- Install [INLA](http://www.r-inla.org/)
```
install.packages("INLA", repos=c(getOption("repos"), INLA="https://inla.r-inla-download.org/R/stable"), dep=TRUE)
```
- Install [Rgraphviz](http://www.bioconductor.org/packages/release/bioc/html/Rgraphviz.html)
```
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("Rgraphviz", version = "3.8")
```
- Install [JAGS](http://mcmc-jags.sourceforge.net/). Operating System dependant
