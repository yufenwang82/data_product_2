---
title       : "Peer-graded Assignment: R Markdown Presentation & Plotly"
subtitle    : 
author      : Yu-Fen Wang
job         : 
date        : "2017/11/3" 
framework   : html5slides        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight  # {highlight.js,prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz, bootstrap]# {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---





## Peer-graded Assignment: R Markdown Presentation & Plotly

### Author: Yu-Fen Wang

### Date: 2017/11/3

--- .class #id  

## demo plot mtcar with plotly


```r
library(plotly)
library(datasets)
data(mtcars)
plot<-plot_ly(mtcars,x=~cyl,y=~mpg,type = "bar")
print(plot)
```
---
