## Test environments
* local Ubuntu 20.10 (linux): R 3.6.3, R 4.0.3 patched, R-devel 4.1.0
* win-builder.r-project.org (windows): oldrel, release, devel
* appveyor (windows): bioc-devel, bioc-release, bioc-oldrel,
    oldrel, release, devel

## R CMD check results

0 errors | 0 warnings | 1 note

* checking package dependencies ... NOTE
Packages suggested but not available for checking:
  'BiocVersion', 'remotes', 'rmarkdown', 'curl'

`BiocVersion` is only available in Bioconductor.

