# Chi-square goodness of fit AND Chi-square test of independence

## Chi-square test of independence (association)

#### Calculate the standardized residuals

Standardized residuals allow us to see which cells are most influential
and aid in interpreting the meaning of the result. Jamovi doesn’t
calculate those automatically yet. (SPSS does.) We can calculate them
manually. The formula is (observed frequency - expected
frequency)/sqrt(expected frequency). As any standardized score, values 2
or greater are extreme values and should be reported as being
significant contributers to significant tests. Positive scores are
higher than expected and negative scores are lower than expected.

``` r
# Food as reward - No
(10-23.6)/sqrt(23.6)
```

    ## [1] -2.799516

``` r
# Food as reward - Yes
(23-14.4)/sqrt(14.4)
```

    ## [1] 2.266299

``` r
# Affection as reward - No
(114-100.4)/sqrt(100.4)
```

    ## [1] 1.357288

``` r
# Affection as reward - Yes
(48-61.6)/sqrt(61.6)
```

    ## [1] -1.7328

## Save your output from RStudio.

## Submit your assignment.

Submit the RStudio .html output you just saved and your Jamovi .omv file
for your assignment.
