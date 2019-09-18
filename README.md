# mlr3-learndrake

<!-- badges: start -->
<!-- badges: end -->

The goal of mlr3-learndrake is to show how to use the [mlr3](https://github.com/mlr-org/mlr3) package framework in combination with the workflow package [drake](https://github.com/ropensci/drake).

## Usage

To clone this course, excecute the following code locally

```r
usethis::use_course("mlr-org/mlr3-learndrake")
```

To make sure you have installed all required packages, call

```r
devtools::install_dev_deps()
```

To open the respective example projects, call one of the following

```r
rstudioapi::openProject("01-intro", newSession = TRUE)
rstudioapi::openProject("02-benchmark", newSession = TRUE)
rstudioapi::openProject("03-pipelines", newSession = TRUE)
```

## Slides

[drake](https://raw.githack.com/mlr-org/mlr3-learndrake/master/slides/drake/index.html)  <img src="https://docs.ropensci.org/drake/reference/figures/logo.svg" alt="logo" height = "15">

[mlr3](https://raw.githack.com/mlr-org/mlr-outreach/master/2019_whyr_warsaw/slides/whyr2019_mlr3.html) 
<img src="https://raw.githubusercontent.com/mlr-org/mlr/master/man/figures/logo_navbar.png" alt="logo" height="10">

# Acknowledgements

- [Will Landau](https://github.com/wlandau) for developing and maintaing _drake_ in an awesome way
- [Garrick Aden-Buie](https://github.com/gadenbuie) for the great slides about _drake_
- [The mlr3 team](https://github.com/mlr-org/mlr3) for developing the mlr3 package framework
