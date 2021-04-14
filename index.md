---
layout: page
title: ρsychμeta
subtitle: Psychometric Meta-Analysis Toolkit
use-site-title: true
---

[![CRAN Version](https://www.r-pkg.org/badges/version/psychmeta)](https://cran.r-project.org/package=psychmeta)
[![Build Status](https://travis-ci.org/psychmeta/psychmeta.svg?branch=master)](https://travis-ci.org/psychmeta/psychmeta)
[![Total Downloads](https://cranlogs.r-pkg.org/badges/grand-total/psychmeta)](https://cranlogs.r-pkg.org/badges/grand-total/psychmeta)
[![Monthly Downloads](https://cranlogs.r-pkg.org/badges/psychmeta)](https://cranlogs.r-pkg.org/badges/psychmeta)

## About psychmeta
The `psychmeta` package provides tools for computing bare-bones and psychometric meta-analyses and for generating psychometric data for use in meta-analysis simulations. Currently, the package supports bare-bones, individual-correction, and artifact-distribution methods for meta-analyzing correlations and *d* values. Please refer to the [overview tutorial vignette](https://cran.r-project.org/web/packages/psychmeta/vignettes/overview.html) for an introduction to `psychmeta`'s functions and workflows.

`psychmeta` is hosted on both [CRAN](https://cran.r-project.org/package=psychmeta) and [GitHub](https://github.com/jadahlke/psychmeta). Documentation for `psychmeta`'s functions is available in the package's [PDF manual](https://cran.r-project.org/web/packages/psychmeta/psychmeta.pdf).

***We're social!*** [Follow psychmeta on Twitter](https://twitter.com/psychmetaR) for news, tips, update announcements, and more.

## Authors
`psychmeta` was written by [Jeffrey A. Dahlke](https://jeffreydahlke.com/) and [Brenton M. Wiernik](https://wiernik.org/).

## Installation Instructions
The official [CRAN release](https://cran.r-project.org/package=psychmeta) of `psychmeta` can be installed with the following code:
```r
install.packages("psychmeta")
```

The unofficial [GitHub release](https://github.com/jadahlke/psychmeta) of `psychmeta` reflects updates made to the package between official CRAN releases. Using the [devtools](https://cran.r-project.org/package=devtools) package, the GitHub release can be installed with the following code:
```r
install.packages("devtools")
devtools::install_github("psychmeta/psychmeta")
```

## Citing psychmeta
To cite `psychmeta` in your research, please refer to the package's citation information using the `citation()` function.
```r
citation("psychmeta")
```

## Reporting Issues
To report a bug or other issue, [tell us about it on GitHub](https://github.com/psychmeta/psychmeta/issues) or email [issues@psychmeta.com](mailto:issues@psychmeta.com). For more general questions and inquiries about the package, reach out to us via [Twitter](https://twitter.com/psychmetaR) or email [psychmeta@psychmeta.com](mailto:psychmeta@psychmeta.com).
