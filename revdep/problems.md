# abjutils

<details>

* Version: 0.2.3
* Source code: https://github.com/cran/abjutils
* URL: https://github.com/abjur/abjutils
* Date/Publication: 2019-02-07 21:43:35 UTC
* Number of recursive dependencies: 73

Run `revdep_details(,"abjutils")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘httr’ ‘progress’
      All declared Imports should be used.
    ```

# adept

<details>

* Version: 1.1.2
* Source code: https://github.com/cran/adept
* URL: https://github.com/martakarass/adept
* BugReports: https://github.com/martakarass/adept/issues
* Date/Publication: 2019-06-18 06:50:03 UTC
* Number of recursive dependencies: 79

Run `revdep_details(,"adept")` for more info

</details>

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.5Mb
      sub-directories of 1Mb or more:
        doc   4.7Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tibble’
      All declared Imports should be used.
    ```

# aroma.affymetrix

<details>

* Version: 3.2.0
* Source code: https://github.com/cran/aroma.affymetrix
* URL: https://www.aroma-project.org/, https://github.com/HenrikBengtsson/aroma.affymetrix
* BugReports: https://github.com/HenrikBengtsson/aroma.affymetrix/issues
* Date/Publication: 2019-06-23 06:00:14 UTC
* Number of recursive dependencies: 74

Run `revdep_details(,"aroma.affymetrix")` for more info

</details>

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.8Mb
      sub-directories of 1Mb or more:
        R             2.3Mb
        help          1.1Mb
        testScripts   1.3Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Error in setGeneric("getX", function(object, type) standardGeneric("getX")) : 
      could not find function "setGeneric"
    ```

# aroma.core

<details>

* Version: 3.2.0
* Source code: https://github.com/cran/aroma.core
* URL: https://github.com/HenrikBengtsson/aroma.core, https://www.aroma-project.org/
* BugReports: https://github.com/HenrikBengtsson/aroma.core/issues
* Date/Publication: 2019-06-17 18:20:03 UTC
* Number of recursive dependencies: 45

Run `revdep_details(,"aroma.core")` for more info

</details>

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      'sfit', 'expectile', 'HaarSeg', 'mpcbs'
    ```

# BAMBI

<details>

* Version: 2.1.0
* Source code: https://github.com/cran/BAMBI
* URL: https://arxiv.org/abs/1708.07804
* BugReports: https://github.com/c7rishi/BAMBI/issues
* Date/Publication: 2019-03-16 20:43:42 UTC
* Number of recursive dependencies: 37

Run `revdep_details(,"BAMBI")` for more info

</details>

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.5Mb
      sub-directories of 1Mb or more:
        libs   4.9Mb
    ```

# brms

<details>

* Version: 2.9.0
* Source code: https://github.com/cran/brms
* URL: https://github.com/paul-buerkner/brms, http://discourse.mc-stan.org
* BugReports: https://github.com/paul-buerkner/brms/issues
* Date/Publication: 2019-05-23 05:00:27 UTC
* Number of recursive dependencies: 163

Run `revdep_details(,"brms")` for more info

</details>

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.4Mb
      sub-directories of 1Mb or more:
        R     2.9Mb
        doc   2.6Mb
    ```

# codebook

<details>

* Version: 0.8.1
* Source code: https://github.com/cran/codebook
* URL: https://github.com/rubenarslan/codebook
* BugReports: https://github.com/rubenarslan/codebook/issues
* Date/Publication: 2019-05-21 12:50:03 UTC
* Number of recursive dependencies: 172

Run `revdep_details(,"codebook")` for more info

</details>

## In both

*   checking examples ... ERROR
    ```
    ...
    > ### ** Examples
    > 
    > example("labelled", "haven")
    
    lablld> s1 <- labelled(c("M", "M", "F"), c(Male = "M", Female = "F"))
    
    lablld> s2 <- labelled(c(1, 1, 2), c(Male = 1, Female = 2))
    
    lablld> s3 <- labelled(c(1, 1, 2), c(Male = 1, Female = 2),
    lablld+                label="Assigned sex at birth")
    
    lablld> # Unfortunately it's not possible to make as.factor work for labelled objects
    lablld> # so instead use as_factor. This works for all types of labelled vectors.
    lablld> as_factor(s1)
    [1] Male   Male   Female
    Levels: Female Male
    
    lablld> as_factor(s1, labels = "values")
    Error: 1 components of `...` were not used.
    
    We detected these problematic arguments:
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘graphics’ ‘jsonlite’ ‘pander’ ‘rlang’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 65 marked UTF-8 strings
    ```

# datapackage.r

<details>

* Version: 0.1.1
* Source code: https://github.com/cran/datapackage.r
* URL: https://github.com/frictionlessdata/datapackage-r
* BugReports: https://github.com/frictionlessdata/datapackage-r/issues
* Date/Publication: 2019-05-20 16:40:03 UTC
* Number of recursive dependencies: 97

Run `revdep_details(,"datapackage.r")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘future’ ‘iterators’ ‘readr’
      All declared Imports should be used.
    ```

# fxtract

<details>

* Version: 0.9.1
* Source code: https://github.com/cran/fxtract
* URL: https://github.com/QuayAu/fxtract
* BugReports: https://github.com/QuayAu/fxtract/issues
* Date/Publication: 2019-02-12 17:30:03 UTC
* Number of recursive dependencies: 78

Run `revdep_details(,"fxtract")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘future’ ‘utils’
      All declared Imports should be used.
    ```

# GetBCBData

<details>

* Version: 0.5
* Source code: https://github.com/cran/GetBCBData
* URL: https://github.com/msperlin/GetBCBData/
* BugReports: https://github.com/msperlin/GetBCBData/issues
* Date/Publication: 2019-04-23 10:10:29 UTC
* Number of recursive dependencies: 97

Run `revdep_details(,"GetBCBData")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘RCurl’ ‘lubridate’ ‘readr’ ‘stats’
      All declared Imports should be used.
    ```

# grattan

<details>

* Version: 1.7.1.2
* Source code: https://github.com/cran/grattan
* URL: https://github.com/HughParsonage/grattan, https://hughparsonage.github.io/grattan/
* BugReports: https://github.com/HughParsonage/grattan/issues
* Date/Publication: 2019-05-20 18:00:03 UTC
* Number of recursive dependencies: 101

Run `revdep_details(,"grattan")` for more info

</details>

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      'taxstats', 'taxstats1516'
    ```

# infercnv

<details>

* Version: 1.0.2
* Source code: https://github.com/cran/infercnv
* URL: https://github.com/broadinstitute/inferCNV/wiki
* BugReports: https://github.com/broadinstitute/inferCNV/issues
* Date/Publication: 2019-05-21
* Number of recursive dependencies: 116

Run `revdep_details(,"infercnv")` for more info

</details>

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.0Mb
      sub-directories of 1Mb or more:
        extdata   3.1Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported object imported by a ':::' call: ‘HiddenMarkov:::makedensity’
      See the note in ?`:::` about the use of this operator.
    ```

# lidR

<details>

* Version: 2.0.3
* Source code: https://github.com/cran/lidR
* URL: https://github.com/Jean-Romain/lidR
* BugReports: https://github.com/Jean-Romain/lidR/issues
* Date/Publication: 2019-05-09 18:30:07 UTC
* Number of recursive dependencies: 138

Run `revdep_details(,"lidR")` for more info

</details>

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 10.6Mb
      sub-directories of 1Mb or more:
        libs   7.7Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘Rcpp’
      All declared Imports should be used.
    ```

# MetamapsDB

<details>

* Version: 0.0.2
* Source code: https://github.com/cran/MetamapsDB
* Date/Publication: 2017-12-06 09:51:00 UTC
* Number of recursive dependencies: 108

Run `revdep_details(,"MetamapsDB")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Matrix’ ‘shiny’
      All declared Imports should be used.
    ```

# photosynthesis

<details>

* Version: 1.0.0
* Source code: https://github.com/cran/photosynthesis
* Date/Publication: 2019-05-09 15:10:03 UTC
* Number of recursive dependencies: 64

Run `revdep_details(,"photosynthesis")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

# phylolm

<details>

* Version: 2.6
* Source code: https://github.com/cran/phylolm
* URL: https://CRAN.R-project.org/package=phylolm
* Date/Publication: 2018-05-31 04:51:24 UTC
* Number of recursive dependencies: 19

Run `revdep_details(,"phylolm")` for more info

</details>

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘surface’, ‘bayou’, ‘geiger’, ‘caper’
    ```

# promises

<details>

* Version: 1.0.1
* Source code: https://github.com/cran/promises
* URL: https://rstudio.github.io/promises, https://github.com/rstudio/promises
* BugReports: https://github.com/rstudio/promises/issues
* Date/Publication: 2018-04-13 08:59:30 UTC
* Number of recursive dependencies: 32

Run `revdep_details(,"promises")` for more info

</details>

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘purrr’
    ```

# Prostar

<details>

* Version: 1.16.6
* Source code: https://github.com/cran/Prostar
* Date/Publication: 2019-06-19
* Number of recursive dependencies: 253

Run `revdep_details(,"Prostar")` for more info

</details>

## In both

*   checking whether package ‘Prostar’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: no DISPLAY variable so Tk is not available
    See ‘/home/hb/repositories/future/revdep/checks/Prostar/new/Prostar.Rcheck/00install.out’ for details.
    ```

# QDNAseq

<details>

* Version: 1.20.0
* Source code: https://github.com/cran/QDNAseq
* URL: https://github.com/ccagc/QDNAseq
* BugReports: https://github.com/ccagc/QDNAseq/issues
* Date/Publication: 2019-05-02
* Number of recursive dependencies: 66

Run `revdep_details(,"QDNAseq")` for more info

</details>

## In both

*   checking for missing documentation entries ... WARNING
    ```
    Undocumented code objects:
      ‘exportVCF’
    All user-level objects in a package should have documentation entries.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

# robotstxt

<details>

* Version: 0.6.2
* Source code: https://github.com/cran/robotstxt
* URL: https://github.com/ropensci/robotstxt
* BugReports: https://github.com/ropensci/robotstxt/issues
* Date/Publication: 2018-07-18 21:30:03 UTC
* Number of recursive dependencies: 53

Run `revdep_details(,"robotstxt")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘future’
      All declared Imports should be used.
    ```

# sapfluxnetr

<details>

* Version: 0.0.7
* Source code: https://github.com/cran/sapfluxnetr
* URL: https://github.com/sapfluxnet/sapfluxnetr
* BugReports: https://github.com/sapfluxnet/sapfluxnetr/issues
* Date/Publication: 2019-05-01 10:40:03 UTC
* Number of recursive dependencies: 96

Run `revdep_details(,"sapfluxnetr")` for more info

</details>

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 4 marked UTF-8 strings
    ```

# sctransform

<details>

* Version: 0.2.0
* Source code: https://github.com/cran/sctransform
* URL: https://github.com/ChristophH/sctransform
* BugReports: https://github.com/ChristophH/sctransform/issues
* Date/Publication: 2019-04-12 12:32:38 UTC
* Number of recursive dependencies: 46

Run `revdep_details(,"sctransform")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Rcpp’ ‘future’
      All declared Imports should be used.
    ```

# Seurat

<details>

* Version: 3.0.2
* Source code: https://github.com/cran/Seurat
* URL: http://www.satijalab.org/seurat, https://github.com/satijalab/seurat
* BugReports: https://github.com/satijalab/seurat/issues
* Date/Publication: 2019-06-14 22:22:02 UTC
* Number of recursive dependencies: 197

Run `revdep_details(,"Seurat")` for more info

</details>

## In both

*   checking Rd cross-references ... WARNING
    ```
    Unknown package ‘loomR’ in Rd xrefs
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘loomR’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 10.5Mb
      sub-directories of 1Mb or more:
        libs   9.0Mb
    ```

# shinyrecap

<details>

* Version: 0.1.0
* Source code: https://github.com/cran/shinyrecap
* URL: https://fellstat.github.io/shinyrecap/
* Date/Publication: 2019-01-19 23:40:03 UTC
* Number of recursive dependencies: 76

Run `revdep_details(,"shinyrecap")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘CARE1’ ‘LCMCR’ ‘coda’ ‘conting’ ‘dga’ ‘future’ ‘ggplot2’ ‘ipc’
      ‘promises’ ‘reshape’ ‘shinycssloaders’ ‘testthat’
      All declared Imports should be used.
    ```

# simglm

<details>

* Version: 0.7.4
* Source code: https://github.com/cran/simglm
* Date/Publication: 2019-05-31 17:10:03 UTC
* Number of recursive dependencies: 77

Run `revdep_details(,"simglm")` for more info

</details>

## In both

*   checking Rd cross-references ... WARNING
    ```
    Missing link or links in documentation object 'sim_pow.Rd':
      ‘corStruct’
    
    Missing link or links in documentation object 'sim_pow_nested.Rd':
      ‘corStruct’
    
    Missing link or links in documentation object 'sim_pow_nested3.Rd':
      ‘corStruct’
    
    See section 'Cross-references' in the 'Writing R Extensions' manual.
    ```

# skpr

<details>

* Version: 0.57.0
* Source code: https://github.com/cran/skpr
* URL: https://github.com/tylermorganwall/skpr
* BugReports: https://github.com/tylermorganwall/skpr/issues
* Date/Publication: 2018-11-13 19:20:03 UTC
* Number of recursive dependencies: 120

Run `revdep_details(,"skpr")` for more info

</details>

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 49.1Mb
      sub-directories of 1Mb or more:
        libs  47.6Mb
    ```

# stars

<details>

* Version: 0.3-1
* Source code: https://github.com/cran/stars
* URL: https://github.com/r-spatial/stars/
* BugReports: https://github.com/r-spatial/stars/issues/
* Date/Publication: 2019-04-23 12:30:03 UTC
* Number of recursive dependencies: 109

Run `revdep_details(,"stars")` for more info

</details>

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking: 'plm', 'starsdata'
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 16.0Mb
      sub-directories of 1Mb or more:
        doc  10.5Mb
        nc    4.2Mb
    ```

# tableschema.r

<details>

* Version: 1.1.0
* Source code: https://github.com/cran/tableschema.r
* URL: https://github.com/frictionlessdata/tableschema-r
* BugReports: https://github.com/frictionlessdata/tableschema-r/issues
* Date/Publication: 2018-11-14 16:50:03 UTC
* Number of recursive dependencies: 43

Run `revdep_details(,"tableschema.r")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘iterators’
      All declared Imports should be used.
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘parsedate’
    ```

# tealeaves

<details>

* Version: 1.0.0
* Source code: https://github.com/cran/tealeaves
* Date/Publication: 2019-05-04 16:40:03 UTC
* Number of recursive dependencies: 62

Run `revdep_details(,"tealeaves")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘ggplot2’ ‘tidyr’
      All declared Imports should be used.
    ```

# threeBrain

<details>

* Version: 0.1.2
* Source code: https://github.com/cran/threeBrain
* Date/Publication: 2019-06-28 16:40:02 UTC
* Number of recursive dependencies: 34

Run `revdep_details(,"threeBrain")` for more info

</details>

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.2Mb
      sub-directories of 1Mb or more:
        htmlwidgets   4.7Mb
    ```

# TSstudio

<details>

* Version: 0.1.4
* Source code: https://github.com/cran/TSstudio
* Date/Publication: 2019-04-13 16:22:38 UTC
* Number of recursive dependencies: 128

Run `revdep_details(,"TSstudio")` for more info

</details>

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘purrr’
      All declared Imports should be used.
    ```

