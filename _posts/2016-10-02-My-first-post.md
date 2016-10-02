---
layout: post
title: My first post
author: Peter Laurinec
published: true
status: publish
draft: false
tags: R
---
 
## Data Analysis
 
Generate some random numbers:
 

    rnorm(50)
 

    ##  [1] -0.729024198  0.665164059 -0.186854680 -1.075132563 -0.596832998
    ##  [6] -1.035265398  2.106080072 -1.465861813  0.739433404 -0.169980161
    ## [11]  0.009175699 -1.894993740  0.047046196 -0.607118785  0.917589617
    ## [16] -0.144119753 -0.293812273 -1.354508491 -1.169470526  0.897495948
    ## [21]  0.004097673  1.896760239  0.050538490 -0.167091959 -1.017317653
    ## [26]  0.804640075  1.296759251  0.256770380  0.777429601  0.111045824
    ## [31]  0.318471513 -0.210567687 -0.672690824 -0.914658829 -0.576002407
    ## [36]  0.191481487 -1.270657801 -0.035131208  0.959473052 -0.175848602
    ## [41]  1.265881629 -0.202382311  0.279092747  0.325758770 -0.346375292
    ## [46]  0.683197840  0.550907679 -0.236807734  0.677134545  0.459877991
 
## Ploting time series
 
Plot random numbers like time series:
 

    plot(ts(timeseries_1, start = 0), ylab = "", xlab = "Time")

![plot of chunk plot](/images/plot-1.png)