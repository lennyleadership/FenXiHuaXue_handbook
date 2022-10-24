---
weight: 68
title: 68 Choosing the Newxt Design
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
  <img src = "/docs/images/Screenshot 2022-10-24 155020.png" HSPACE="10" VSPACE="10"/> 
</div>
The next step in this study is to design a new experiment with a lower number of factors to assess their effect on wine quality. The question is: which factors we should  keep for the next design? Let's start answering it with the factors that we shouldn't keep. First, the ones that were not significant:  The age of the barrel and the barrel toast. It is pointless to keep them in the design.
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 155316.png" HSPACE="10" VSPACE="10"/> 
  <img src = "/docs/images/Screenshot 2022-10-24 155413.png" HSPACE="10" VSPACE="10"/>
</div>
The second group of factors that we should not study is the ones that affected the wine rank and that we have a definite conclusion about their effect.  In this case, the yeast showed the strongest effect,  and it seems pretty clear that the Montrachet one results in the best-ranked wine.  So we don't need to test the yeast anymore and should use the Montrachet in the next design.
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 155515.png" HSPACE="10" VSPACE="10"/> 
</div>
The real question mark is about the temperature and the presence of stems.  It seems that no stems and low temperature results in the best wine. However, the results are not as conclusive as the effect of the yeast, and we have potential interactions happening.  
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 155704.png" HSPACE="10" VSPACE="10"/> 
</div>
The other factors were significant at a low level, so we need to study them better.  
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 160034.png" HSPACE="10" VSPACE="10"/> 
</div>
In a nutshell, the age of the barrel and the  barrel toast do not affect the wine rank. The yeast has the strongest effect,  and the Montrachet is the best. We don't need to study it anymore.  The Pinot Noir clone, the oak type, and the whole cluster need to be studied and should be kept in the next design.  The decision is in the fermentation temperature and the presence of stems.  
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 160321.png" HSPACE="10" VSPACE="10"/> 
</div>
We can use them in the next design, and then we will have five factors to be studied.  If we can run 16 experiments again, we will have a 2<sup>5-1</sup> fractional design.  
</div> 



<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 160508.png" HSPACE="10" VSPACE="10"/> 
</div>
The 2<sup>5-1</sup> fractional design is a resolution V design, where we don't have main factors and two-factor interactions aliased to each other. It is almost as good as a full design.  So, I would not even think about using the fermentation temperature  and the stems fixed in the next design, as maybe there are some important interactions  among them and the other factors.
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 160617.png" HSPACE="10" VSPACE="10"/> 
</div>
In conclusion, for the 1986 Pinot Noir,  I would recommend a 2ˆ(5−1) resolution V fractional design with 16 runs.  
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 160837.png" HSPACE="10" VSPACE="10"/> 
</div>
The last part of the R code is building this 2<sup>5-1</sup> fractional design. Let's do it.  We are building a fractional design with five factors and resolution 5.  The resulting table shows the treatments in random order and coded as A, B, C, D, and E, with the levels negative one and positive one. As the last step, let's add the factor names and levels to this design. The next code lines create columns for the natural factors: Pinot Noir clone as factor A, Oak type as factor B, and so on,  and use the levels of the coded factors to set the levels of the natural factors.  Let's run it.  
</div> 

And here we have the experimental table ready. We just need to save it and run the experiments!  Fractional designs are challenging to build and to analyse;  however, they can be extremely useful to get significant insights into the factors that affect a particular system and that are worthy of our attention.  I hope this whole section was useful to you. Stay well, and I see you next time.  
