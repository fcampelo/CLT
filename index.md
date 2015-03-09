---
title       : Central Limit Theorem
subtitle    : A demonstration using Shiny Apps
logo        : logo.png
author      : Felipe Campelo, Ph.D.
job1        : Dept. Electrical Engineering
job2        : Universidade Federal de Minas Gerais
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]     # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Summary

This document presents a demo app for the Central Limit Theorem (CLT), developed using [Shiny Apps](http://shiny.rstudio.com/) on [RStudio](http://rstudio.com/).

Students can explore different probability distributions and sample sizes, and verify that the sampling distribution of means will be approximately normal with specific means/variances regardless of the distribution shape of the original data.

---

## Relevance

The [CLT](http://www.encyclopediaofmath.org/index.php/Central_limit_theorem) is an important result in statistical theory which, besides being quite interesting by itself, is also immensely useful in inference since it allows us to employ methods based on normal distributions to inferences about the means of non-normal populations.

A quick definition of the CLT:
<center><font size=5>
Let $y_1,\ldots,y_n$ be a sequence of independent and identically distributed (iid)<br/>random variables,with mean $\mu$ and finite variance $\sigma^2$. Then:
</font></center>
$$z_n = \frac{\sum{y_i} - n\mu}{\sqrt{n\sigma^2}}$$
<center><font size=5>is distributed approximately as a standard normal variable, that is, $z_n\sim\mathcal{N}(0,1)$.</font></center>

---

## The app
You can find the app on [shinyapps.io](https://fcampelo.shinyapps.io/CLT_demo/) as well as on [my personal server](http://drwho.cpdee.ufmg.br:3838/CLT/). The source code is available from [Github](https://github.com/fcampelo/CLT). It looks something like this (with some code and a short description too. Go check the real thing!):

<center><img src="assets/img/CLTdemo.png" alt="App screenshot" width=85%></center>

---

## To know more

- About the CLT: [Wikipedia](http://en.wikipedia.org/wiki/Central_limit_theorem), [Wolfram Mathworld](http://mathworld.wolfram.com/CentralLimitTheorem.html);  
- About Shiny: [Shiny Apps](http://shiny.rstudio.com/);  
- About Slidify (which was used to make these slides): [Slidify](http://slidify.org);  
- About the author: [My profile](http://drwho.cpdee.ufmg.br/joomla/index.php/felipe-campelo), [My publications](http://buscatextual.cnpq.br/buscatextual/visualizacv.do?metodo=apresentar&id=K4762838H8#ArtigosCompletos).

