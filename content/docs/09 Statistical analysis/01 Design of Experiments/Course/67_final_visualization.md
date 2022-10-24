---
weight: 67
title: 67 Final Visualisation of the Results
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

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 153105.png" HSPACE="10" VSPACE="10"/> 
</div>
To build a final presentation of the results is not always an easy task, and we probably need to try more than one plot until reaching a suitable output.  After some trials, I have come with the following. Using the table with the regression coefficients,  I have chosen the three factors with the strongest influence in the rank: the yeast, the fermentation temperature, and the stems.
</div> 

For this final analysis, we are going to use two more R packages, the dplyr and the ggplot2. Let's load them.  
<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 153332.png" HSPACE="10" VSPACE="10"/> 
</div>
First, we are going to build a table with the summarised results for these three factors, the mean, the standard deviation and the number of observations.
</div> 

The new table has eight treatments, the combination of the low and high levels of the three factors D, E, and G, and each treatment has two observations.  

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 153623.png" HSPACE="10" VSPACE="10"/> 
</div>
Let's now create columns with the natural variables using the coded variables as a template.  Yeast is factor D, Temperature is factor E, and Stem is factor G.  And here we have the table with the natural variables.  
</div> 


<br>
<center><img width = "540", src = "/docs/images/Screenshot 2022-10-24 153733.png" /></center>

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 154133.png" HSPACE="10" VSPACE="10"/> 
</div>
Finally, let's build the bar plot. An important remark here:  all variables in this experiment are categorical, we cannot use contour-plots.  For the bar plot, we are using ggplot. I have chosen the Stem for the x-axis,  the y-axis is the mean, and we are going to colour the bars according to the yeast type.  We are adding the error bars as the standard deviation between the two observations,  and we are going to split the results by the temperature and the yeast type.  Let's run it.
</div> 


<br>
The result is this very beautiful plot. At the left, we have the yeast Champagne,  and at the right, the Montrachet one. The two upper plots show the results for low temperature,  and the two lower plots, for high temperature. The x-axis is the stems.  And this plot shows a very interesting result: the combination of low temperature, absence of  Stem, and yeast Montrachet results in the best-ranked wine (low is better), but moreover,  with almost no effect of the other variables, as can be seen by the low standard deviation. 
