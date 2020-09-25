test\_markdown
================
E. Bendall
25/09/2020

``` r
## test chunk

vector <- seq(1:10)

library(dplyr)
```

    ## 
    ## Attaching package: 'dplyr'

    ## The following objects are masked from 'package:stats':
    ## 
    ##     filter, lag

    ## The following objects are masked from 'package:base':
    ## 
    ##     intersect, setdiff, setequal, union

``` r
vector.avg <- vector * 10
```

``` r
plot(vector.avg)
```

![](test_markdown_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->
