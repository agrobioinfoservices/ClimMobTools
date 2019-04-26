
ClimMobTools
============

[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/kauedesousa/ClimMobTools?branch=master&svg=true)](https://ci.appveyor.com/project/kauedesousa/ClimMobTools)

Package website: <https://kauedesousa.github.io/ClimMobTools/>

Overview
--------

The **ClimMobTools** package provides the toolkit employed in crowdsourcing citizen science projects under the *tricot* approach. Tricot, stands for "triadic comparison of technologies" for the rapid assessment of on-farm evaluation trails in small-scale agriculture.

Installation
------------

The development version can be installed via

    library("devtools")
    devtools::install_github("kauedesousa/ClimMobTools", upgrade = "never")

To enable the vignettes to be build use

    library("devtools")
    devtools::install_github("kauedesousa/ClimMobTools", 
                             build_opts = c("--no-resave-data", "--no-manual"),
                             upgrade = "never")

**ClimMobTools** is under development. Use with caution.

Going further
-------------

The full functionality of **ClimMobTools** is illustrated in the package vignette. The vignette can be found on the [package website](https://kauedesousa.github.io/ClimMobTools/) or from within `R` once the package has been installed, e.g. via

    vignette("Overview", package = "ClimMobTools")

Code of Conduct
---------------

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.
