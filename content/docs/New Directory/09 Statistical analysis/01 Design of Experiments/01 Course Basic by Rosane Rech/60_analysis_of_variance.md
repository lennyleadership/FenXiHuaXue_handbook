---
weight: 60
title: 60 Analysis of Variance
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
Section 8: Fractional Designs 

<!--more-->
---

Let’s start our analysis of the 2<sup>4-1</sup> design by opening the CSV file with the data. In the datafile we have our coded variables: xT, xP, xC and xW,  the natural variables temperature, pressure, concentration, and stirring rate, and our response variable, FR. Let's now take a look in the file structure. Here we have that the file has eight observations of nine variables, and all variables are numerical. As we need variables as factors for the analysis of variance, we are going to create Factor_T, Factor_P, Factor_C, and Factor_W using the natural variables, temperature, pressure, concentration, and stirring rate to set the levels. Let’s run it. Now our file has 8 observations of 13 variables,and we have here the new variables Factor_T, Factor_P, Factor_C, and Factor_W; as factors with 2 levels each.  
<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 122858.png" HSPACE="10" VSPACE="10"/> 
</div>
Let's now run the analysis of variance. 
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 123101.png" HSPACE="10" VSPACE="10"/> 
</div>
The analysis of variance was run for the full factorial design: main factors, two-factor interactions, three-factor interactions, the four-factor interaction. However, the resulting ANOVA Table shows only the main effects and three of the six two-factor interactions. So, where is the rest? We can see that the table presents only seven degrees of freedom. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 123328.png" HSPACE="10" VSPACE="10"/> 
</div>
This is because the experimental matrix of a 2^(4−1) design has only eight runs, so the degrees of freedom of the design is eight minus one, seven. There is no degrees of freedom available to calculate the sum of squares of the remaining interactions. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 123500.png" HSPACE="10" VSPACE="10"/> 
</div>
Let’s do a different approach and run the regression model of this design.
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 123619.png" HSPACE="10" VSPACE="10"/> 
</div>
We have also run the full design in the regression model, even though, the model has only eight coefficients: the intercept and seven coefficients related to main factors or interactions. The remaining coefficients cannot be estimated as we don’t have degrees of freedom for them. In addition, we got a warning that there are no degrees of freedom in the residuals. And as consequence, the R-squared is 1, there is no evaluation of the error in the system.
</div> 

