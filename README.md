
<!-- README.md is generated from README.Rmd. Please edit that file -->

[![Travis-CI Build
Status](https://travis-ci.org/SMAC-Group/introDS.svg?branch=master)](https://travis-ci.org/SMAC-Group/introDS)
[![Project Status:
Active](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Licence](https://img.shields.io/badge/licence-AGPL--3.0-blue.svg)](https://opensource.org/licenses/AGPL-3.0)
[![minimal R
version](https://img.shields.io/badge/R%3E%3D-3.5.0-6666ff.svg)](https://cran.r-project.org/)

# Introduction to Data Science 😎

The objective of the `introDS` package is to provide a support for the
course entitled “Introduction to Data Science” given at University of
Geneva. This course is intended to provide an introduction to
statistical programming using the R language. It will also provide
students with notions of data management, manipulation and analysis as
well as of reproducible research, result-sharing and version control
(using GitHub). At the end of the class, students should be able to
automatically extract data from websites and create interactive web apps
as well as dynamic reports to visualize and analyze them. Students
should also be able to construct their own R packages, make them
available on GitHub and document them using literate programming.

# Installation Instructions 💻

The `introDS` package is currently only available on GitHub. This
version can be installed as follows:

``` r
# Install dependencies
install.packages(c("devtools","knitr","rmarkdown"))

# Install the package from GitHub
devtools::install_github("SMAC-Group/introDS")
```
