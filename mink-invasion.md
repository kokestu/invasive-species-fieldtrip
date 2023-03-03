Modelling the invasive American Mink in the Pyrenees
================

## The model

This model is taken from [Catford et
al. 2018](http://www.nature.com/articles/s41467-018-04491-3).

  
![\\frac{\\textrm{d}p\_i}{\\textrm{d}t} = 
\\left( c\_i p\_i + h\_i \\right) \\left( 1 - \\sum\_{j = 1}^{i} p\_j
\\right) -
\\left( m\_i + \\sum\_{j = 1}^{i-1} c\_j p\_j + h\_j \\right)
p\_i](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Cfrac%7B%5Ctextrm%7Bd%7Dp_i%7D%7B%5Ctextrm%7Bd%7Dt%7D%20%3D%20%0A%20%20%20%20%20%20%20%20%5Cleft%28%20c_i%20p_i%20%2B%20h_i%20%5Cright%29%20%5Cleft%28%201%20-%20%5Csum_%7Bj%20%3D%201%7D%5E%7Bi%7D%20p_j%20%5Cright%29%20-%0A%20%20%20%20%20%20%20%20%5Cleft%28%20m_i%20%2B%20%5Csum_%7Bj%20%3D%201%7D%5E%7Bi-1%7D%20c_j%20p_j%20%2B%20h_j%20%5Cright%29%20p_i
"\\frac{\\textrm{d}p_i}{\\textrm{d}t} = 
        \\left( c_i p_i + h_i \\right) \\left( 1 - \\sum_{j = 1}^{i} p_j \\right) -
        \\left( m_i + \\sum_{j = 1}^{i-1} c_j p_j + h_j \\right) p_i")  

## GitHub Documents

This is an R Markdown format used for publishing markdown documents to
GitHub. When you click the **Knit** button all R code chunks are run and
a markdown file (.md) suitable for publishing to GitHub is generated.

## Including Code

You can include R code in the document as follows:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](mink-invasion_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
