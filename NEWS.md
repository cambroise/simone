# simone 1.0-5

* Bumped version for CRAN resubmission.
* Updated CITATION file: replaced deprecated `citEntry()`/`personList()` with
  `bibentry()`/`c()`.
* Fixed deprecated `class(x) == "..."` comparisons: replaced with `inherits()`.
* Fixed bare `return` (without parentheses) in `draw.edges()`.
* Replaced dead and non-HTTPS URLs in documentation with DOIs or canonical HTTPS links.
* Fixed lost-brace warning in `rTranscriptData.Rd`.
* Updated maintainer email and minimum R version requirement.

# simone 1.0-4

* Replaced dependency on 'mixer' by 'blockmodels'.
* Registered C functions.

# simone 1.0-3

* Removed use of deprecated arguments in `person()`.

# simone 1.0-2

* Removed use of the deprecated function `as.real` (removed in R 3.0).

# simone 1.0-1

* Fixed warning with R 2.14.

# simone 1.0-0

* Major release: complete rewrite of the package.
* New inference methods: multitask learning, VAR(1) inference.
* New plotting functions for network representation.

# simone 0.1-3

* Minor bug fix in JRx computation.

# simone 0.1-2

* Fixed documentation errors occurring with R-devel (2.9.0 2009-02-19 r47958).

# simone 0.1-1

* First official release.
