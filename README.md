# genpwr

Power and sample size calculations for genetic association studies under genetic model misspecification.

Compatibility updates by Renova.

Version 1.0.4.9001 replaces a `class(yl0) == "list"` comparison in `R/ll_zero_finder.R` with `inherits(yl0, "list")` and lists `gridExtra` under `Suggests`.

## Install

```r
install.packages("genpwr", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/genpwr@renova-1.0.4.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

genpwr is by Camille Moore (maintainer) and Sean Jacobson; the original CRAN package is at <https://CRAN.R-project.org/package=genpwr>. License: GPL-3; see [COPYING](COPYING).
