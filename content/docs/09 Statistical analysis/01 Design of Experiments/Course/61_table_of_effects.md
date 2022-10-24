---
weight: 61
title: 61 Table of Effects
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


<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 124145.png" HSPACE="10" VSPACE="10"/> 
</div>
Now we are going to use the results of the regression model to build <u>a table of effects</u> to help with the analysis. The effect of a factor or interaction can be calculated as twice the regression coefficient,  as we already have done previously. 
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 124343.png" HSPACE="10" VSPACE="10"/> 
</div>
However, the analysis of the effects is not straightforward,  as we have several aliases in this fractional design. Just as to remind, factor A is the temperature, factor B the pressure, factor C the concentration, and factor D the stirring rate. From the aliases of A, we know that the estimated effect of A is indeed the effect of A plus the interaction BCD. Translating to our variables: the estimated effect of the temperature is the effect of the temperature plus the effect of the interaction between pressure, concentration, and stirring rate. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 124604.png" HSPACE="10" VSPACE="10"/> 
</div>
In the same way: the effect of the pressure is the pressure plus the interaction temperature, concentration, and stirring rate. The effect of the concentration is the concentration plus the effect of the temperature, pressure, stirring rate interaction. And the effect of the stirring rate is the stirring rate plus the temperature, pressure, concentration interaction. For the effects of two-factor interactions: temperature-pressure is temperature-pressure plus the concentration stirring rate interaction. The calculated effect of the temperature-concentration is the effect of the temperature-concentration, plus the effect of the pressure stirring rate interaction. And the effect of the pressure-concentration interaction that we have in the table, is pressure-concentration plus the interaction temperature-stirring rate. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 124802.png" HSPACE="10" VSPACE="10"/> 
</div>
Let’s now analyze the implications of the aliasing between effects: The main effects are aliased to three-factor interactions that are not significant, so we are pretty sure that the estimated effects are from the main factors temperature, pressure, concentration, and stirring rate. We can see that the temperature, the concentration, and the stirring rate have strong effects on the filtration rate, while the P has a low or weak effect. As a conclusion, we can say that the main factors that affect the filtration rate are the temperature, concentration, and the stirring rate. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 125040.png" HSPACE="10" VSPACE="10"/> 
</div>
Now let’s look into the two-factor interaction effects: the temperature-pressure effect is the sum of the temperature-pressure and the concentration-stirring rate effects. And it is low, so we have two possibilities here: or both of them affect the result in an inverse way, or neither of them is significant. The second choice is most probable, after all, studies had shown that around 90% of two-factor interactions are not significant. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 125659.png" HSPACE="10" VSPACE="10"/> 
</div>
The next one is the sum of temperature-concentration and pressure-stirring rate interactions. As the resulting effect is high, one of them affects the result. And the question is: which one? temperature-concentration or pressure-stirring rate. As the pressure has a low effect, probably the interaction pressure-stirring rate will also have a low effect, so we are going with the temperature-concentration interaction as significant. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 125847.png" HSPACE="10" VSPACE="10"/> 
</div>
And finally, we have the sum of the effects of the interaction pressure-concentration and temperature-stirring rate. Again, as the resulting effect is high, one of them affects the result: pressure-concentration or temperature-stirring rate. And, again, as the pressure has a low effect, probably the interaction pressure-concentration also has a low effect, so we are going with temperature-stirring. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 130014.png" HSPACE="10" VSPACE="10"/> 
</div>
As a conclusion: the two-factor interactions that affect the response are temperature-concentration and temperature-stirring rate. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 130234.png" HSPACE="10" VSPACE="10"/> 
</div>
Now we can use this information to eliminate the non-significant effects from the ANOVA table, so we are going to run a new analysis of variance with the temperature, the concentration, the stirring rate, the temperature-concentration, and the temperature-stirring rate interaction. The temperature-stirring is shown as pressure-concentration in this ANOVA table. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 130356.png" HSPACE="10" VSPACE="10"/> 
  <img src = "/docs/images/Screenshot 2022-10-24 130543.png" HSPACE="10" VSPACE="10"/> 
</div>
Before analyzing the results, I want to point out that this new ANOVA has taken into account only the factors temperature, concentration, and stirring rate, as the pressure was not significant. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 130735.png" HSPACE="10" VSPACE="10"/> 
</div>
If you look into the experimental matrix and cut out the pressure, we will a full two in the power of three design for temperature, concentration, and stirring rate. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 130844.png" HSPACE="10" VSPACE="10"/> 
</div>
This is the projection propriety we’ve talked at the beginning of this section: Fractional designs can be projected into stronger designs in the subset of significant factors. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 131023.png" HSPACE="10" VSPACE="10"/> 
</div>
Now, finally the analysis of the results: are significant the main factors: temperature, concentration, and stirring rate, and two-factor interactions: temperature-concentration, and temperature-stirring rate. As this is now a single-replicate two in the power of three design, the sum of squares and the degrees of freedom of the error are formed by the merge of the sum of squares and the degrees of freedom of the interaction concentration-stirring rate, and by the three-factor interaction temperature-concentration-stirring rate. 
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 131105.png" HSPACE="10" VSPACE="10"/> 
</div>
These are the same conclusions we had when running the full factorial design. 
</div> 

