A Title

Thomas Rosenthal

March 1, 2021

## Introduction

## Data Exploration

### Dataset

### Exploratory Results

    ## # A tibble: 9 x 2
    ##   Attribute     n
    ##   <chr>     <int>
    ## 1 age          61
    ## 2 altruism     11
    ## 3 cost         19
    ## 4 fitness      28
    ## 5 gender       55
    ## 6 health       31
    ## 7 law          17
    ## 8 status       41
    ## 9 sub_ab       30

    ## # A tibble: 27 x 3
    ## # Groups:   Attribute [9]
    ##    Attribute Value                      n
    ##    <chr>     <chr>                  <int>
    ##  1 age       10                         9
    ##  2 age       40                        24
    ##  3 age       70                        19
    ##  4 age       baby                       9
    ##  5 altruism  donated a kidney           6
    ##  6 altruism  not a registered donor     5
    ##  7 cost      rural                      9
    ##  8 cost      urban                     10
    ##  9 fitness   athletic                   7
    ## 10 fitness   obese                     13
    ## # … with 17 more rows

    ## # A tibble: 27 x 3
    ## # Groups:   Attribute [9]
    ##    Attribute Value                      n
    ##    <chr>     <chr>                  <int>
    ##  1 age       10                       276
    ##  2 age       40                       689
    ##  3 age       70                       352
    ##  4 age       baby                     225
    ##  5 altruism  donated a kidney         146
    ##  6 altruism  not a registered donor   155
    ##  7 cost      rural                    262
    ##  8 cost      urban                    222
    ##  9 fitness   athletic                 162
    ## 10 fitness   obese                    307
    ## # … with 17 more rows

    ##    Attribute                  Value n.x n.y        n
    ## 1        law            law abiding 248   7 35.42857
    ## 2     status                 artist 251   8 31.37500
    ## 3   altruism not a registered donor 155   5 31.00000
    ## 4        age                     10 276   9 30.66667
    ## 5     sub_ab              recovered 183   6 30.50000
    ## 6     status               homeless 268   9 29.77778
    ## 7     status                 doctor 294  10 29.40000
    ## 8    fitness               pregnant 233   8 29.12500
    ## 9       cost                  rural 262   9 29.11111
    ## 10       age                     40 689  24 28.70833
    ## 11    health              excellent 279  10 27.90000
    ## 12    health                average 221   8 27.62500
    ## 13    status                 farmer 137   5 27.40000
    ## 14    gender                   male 701  26 26.96154
    ## 15    gender                 female 744  29 25.65517
    ## 16       age                   baby 225   9 25.00000
    ## 17    sub_ab                 smoker 196   8 24.50000
    ## 18  altruism       donated a kidney 146   6 24.33333
    ## 19   fitness                  obese 307  13 23.61538
    ## 20   fitness               athletic 162   7 23.14286
    ## 21    sub_ab                  drink 205   9 22.77778
    ## 22      cost                  urban 222  10 22.20000
    ## 23       law       criminal history 212  10 21.20000
    ## 24    health                   poor 266  13 20.46154
    ## 25       age                     70 352  19 18.52632
    ## 26    sub_ab            drug addict 126   7 18.00000
    ## 27    status                   exec 107   9 11.88889

<div id="refs" class="references">

<div id="ref-data.table">

Dowle, Matt, and Arun Srinivasan. 2019. *Data.table: Extension of
‘Data.frame‘*. <https://CRAN.R-project.org/package=data.table>.

</div>

<div id="ref-here">

Müller, Kirill. 2017. *Here: A Simpler Way to Find Your Files*.
<https://CRAN.R-project.org/package=here>.

</div>

<div id="ref-R">

R Core Team. 2020. *R: A Language and Environment for Statistical
Computing*. Vienna, Austria: R Foundation for Statistical Computing.
<https://www.R-project.org/>.

</div>

<div id="ref-fuzzyjoin">

Robinson, David. 2020. *Fuzzyjoin: Join Tables Together on Inexact
Matching*. <https://CRAN.R-project.org/package=fuzzyjoin>.

</div>

<div id="ref-tidyverse">

Wickham, Hadley, Mara Averick, Jennifer Bryan, Winston Chang, Lucy
D’Agostino McGowan, Romain François, Garrett Grolemund, et al. 2019.
“Welcome to the tidyverse.” *Journal of Open Source Software* 4 (43):
1686. <https://doi.org/10.21105/joss.01686>.

</div>

<div id="ref-readxl">

Wickham, Hadley, and Jennifer Bryan. 2019. *Readxl: Read Excel Files*.
<https://CRAN.R-project.org/package=readxl>.

</div>

<div id="ref-kableExtra">

Zhu, Hao. 2020. *KableExtra: Construct Complex Table with ’Kable’ and
Pipe Syntax*. <https://CRAN.R-project.org/package=kableExtra>.

</div>

</div>
