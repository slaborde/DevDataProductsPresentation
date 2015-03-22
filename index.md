---
title       : Names Application
subtitle    : How Popular is your name ??
author      : Sebastian Laborde
job         : 
framework   : revealjs      # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : default       # 
widgets     : [nvd3]            # {mathjax, quiz, bootstrap}
ext_widgets : {rCharts: [libraries/nvd3,libraries/morris,libraries/polycharts]}
mode        : standalone # {standalone, draft}
knit        : slidify::knit2slides
---

## Names Application

<span style="color:green; font-weight:bold">Objective:</span>
Answer the question How Popular is your name between 1960 and 2010 ??

## It is easy to use and very funny.

--- .class #id 

## How to use it ??

## The Input:
### You only provide your name and your birth year.


--- .class #id 

## How to use it ??

## The Ouput:

1. **You get the total people (with the name you entered) born in the year you input.** 
2. **In the first tab you get an interactive line chart using NVD3 with the statistics of the name you entered.**
3. **In the second tab you get a donut chart wiht the top 10 popular male names in the year you entered.**
4. **In the third tab you get a donut chart wiht the top 10 popular female names in the year you entered.**

--- .class #id 

## Example

## Line Chart on 3rd Tab for Sebastian




<iframe src=' assets/fig/nvd3plot-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- stat ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>




#### Check it at [shinyapps](https://slaborde.shinyapps.io/workspace/)



