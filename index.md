---
title       : Pitch for Relocator App
subtitle    : St. Louis Rust Belt Relocator App
author      : Karen J Yang
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- .class #id 

## Slide 2


Defining the Problem

     1. There are places that are facing economic decline like St. Louis.
     2. There are people who have little or no job prospects in North St. Louis county or 
        North St. Louis city.
     3. Some people face racial isolation, economic oppression, and police harassment.
     4. Some people are not financially able to relocate on their own.
     5. Outside employers may only consider local job candidates, which makes it 
        that much more important to have the financial wherewithal to move to find work.


--- .class #id 

## Slide 3

```r
xx <- read.csv("unemploy.csv")
```

```
## Warning: incomplete final line found by readTableHeader on 'unemploy.csv'
```

```r
barplot(xx$unemploy.rate,col="darkgreen",names.arg=c("St. Louis City","St. Louis County"))
title(main="Persons Below Poverty Level 2008-2012")
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1.png) 
















--- .class #id 

## Slide 4


Pitch: Solution to Problem

     1. Create a program to help relocate long-term unemployed job seekers.
     2. Offer relocation assistance.



--- .class #id 


## Slide 5

Pitch: Benefit to Society

     1.  Taxpayers have reduced burdens in paying public assistance.
     2.  Employers are able to find employees.
     3.  Job seekers are able to find a job, contribute to paying taxes, and
         may socially benefit from being in a new environment.
         
         
         
Pitch: Conclusion

     1. Help to relocate job seekers who may benefit from living and working in
        a new location.
     2. Create a "win-win" outcome by providing relocation assistance.






