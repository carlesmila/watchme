
[![Build Status](https://travis-ci.org/masalmon/watchme.svg)](https://travis-ci.org/masalmon/watchme)
[![Build status](https://ci.appveyor.com/api/projects/status/6om2pq1kunx4wfuw?svg=true)](https://ci.appveyor.com/project/masalmon/watchme)
[![codecov.io](https://codecov.io/github/masalmon/watchme/coverage.svg?branch=master)](https://codecov.io/github/masalmon/watchme?branch=master)

This package is under development.

# Installation

```r
library("devtools")
install_github("masalmon/watchme", build_vignettes=TRUE)

```


# Introduction

This package aims at supporting the analysis of annotation of images, e.g. pics of wearable camera. The workflow is as follows: 

* pictures are produced, e.g. participants of a study wear a camera that automatically produces pictures;

* these pictures are then annotated by algorithms/ coders using a list of annotations;

* the results of these annotations are then used to e.g. reconstruct the sequence of activities of a person during the day, or link it to pollution exposure.

This R package supports the following tasks:

* How to convert data to a format easier to deal with in R?

* How to summarize annotations?

* How to plot annotations?

* How to calculate interrater agreement? 

This is a minimalist README, but check out the [package website](http://www.masalmon.eu/watchme/) to find more information [about the functions](http://www.masalmon.eu/watchme/reference/index.html), a vignette about [data conversion, summarizing and plotting](http://www.masalmon.eu/watchme/articles/intro.html), another one [about interrater agreement](http://www.masalmon.eu/watchme/articles/interrater_agreement.html), and [one vignette](http://www.masalmon.eu/watchme/articles/chai.html) describing data processing in the [CHAI project](http://www.chaiproject.org/).

## Meta

* Please [report any issues or bugs](https://github.com/masalmon/watchme/issues).
* License: GPL
* Get citation information for `opencage` in R doing `citation(package = 'watchme')`
* Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.



