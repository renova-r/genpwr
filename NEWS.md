# genpwr 1.0.4.9001

Renova release, based on CRAN genpwr 1.0.4 (archived on CRAN 2026-04-11).

- `R/ll_zero_finder.R`: `if(!class(yl0) == "list")` became `if(!inherits(yl0, "list"))`, which avoids comparing a multi-element class vector.
- `DESCRIPTION`: `gridExtra` was added to `Suggests` (metadata only).
- `DESCRIPTION`: `Version` set to `1.0.4.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL text) was added; the `License` field is unchanged.
- `README.md` was replaced by a short Renova README and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.

1.0.0

## Initial version

1.0.1

## Fixed issue with multiple possible answers for power.calc function

1.0.2

## Fixed issue with sqrt in ss.calc function

1.0.3

## Fixed issue which didn't allow some functions to run with R2 instead of ES 

1.0.4

## Added reference to published paper in description
