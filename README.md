# GRaF

GRaF is an R package for fitting species distribution models using Gaussian random fields. There is a version of GRaF [on CRAN](http://cran.r-project.org/web/packages/GRaF/index.html), but this is the development version so 
will get the updates first.

### installing GRaF

To install this development version of GRaF you can use the ```install_github``` function in the [```devtools```](http://cran.r-project.org/web/packages/devtools/index.html) package, like this:

```{r}
# install devtools if you haven't already
# install.packages('devtools')

# load the package
library(devtools)

# install GRaF from github (the version from goldingn's repo at least)
install_github('GRaF', 'goldingn')

# and load it
library(graf)
```

### reporting bugs
If you find a bug in the code or have suggestions for improvements, please let me know via the issues reporting system (button on the right of this page).


### tutorial and other info
I presented a tutorial to GRaF at the INTECOL2013 conference, as well as a reasearch talk on the approach. You can find links to these and a number of other related things over at [the repo I set up](https://github.com/goldingn/intecol2013) for the conference.