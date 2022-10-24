---
weight: 65
title: 65 2^(8-4) Design for Wine Quality
authors: edited by Lenny Lin
categories: 
tags: []
description: null
draft: false
date: "2022-10-24"
lastmod: "2022-10-24"
series: 
toc: true
---
Section 9: Highly Fractionated Designs 

<!--more-->
---

<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 143337.png" HSPACE="10" VSPACE="10"/> 
</div>
In this lesson, we're going to take a look at an experiment that studied the effect of several factors on wine quality using a 2<sup>8-4</sup> fractional design.  The case is the following: Harry owns a vineyard and winery.  He grows several varieties of grapes and produces wine. He is always experimenting  with the wine-making variables to improve his products. This problem describes the  experiment conducted for the 1985 Pinot Noir.   

Eight variables were studied in a 2<sub>*IV*</sub><sup>8-4</sup>  fractional design with 16 runs. The levels of the factors are described in the table:   
Factor A, the pinot noir clone – Pommard or Wandenswil.  
Factor B is the oak type - allier or troncais. 
Factor C is the age of the barrel - old or new.  
Factor D is the yeast/skin contact - Champagne or Montrachet.  
Factor E, the fermentation temperature - low or high.  
Factor F, the presence of the whole cluster - none or 10 %.  
Factor G, the presence of stems – none or all. 
And finally, factor H,  the barrel toast - light or medium. 

The wine was tasted by a panel of experts. Each expert ranked the 16 samples of wine tasted, with rank one being the best.  
</div> 

<br>
Please download and open the R code and the data files and let's jump to R to analyse this problem.  