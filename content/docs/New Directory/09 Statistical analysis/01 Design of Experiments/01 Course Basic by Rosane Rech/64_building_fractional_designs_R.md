---
weight: 64
title: 64 Building Fractional Designs in R
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
  <img src = "/docs/images/Screenshot 2022-10-24 135057.png" HSPACE="10" VSPACE="10"/> 
</div>
To create 2<sup>k</sup> designs in R, we are going to use the FrF2 package, which is a package to build  and to analyse fractional designs. Let's start by loading it.  We can use several different parameters to build fractional designs using the FrF2 function.  In this tutorial, we are going to see how to use some basic ones, as the number of factors, the  number of treatments, and design the resolution.   

Let's start by building the fractional design of the previous video, 2<sup>(5-2)</sup>, using as arguments the number of factors and the number of runs.  It will return the design with the highest possible resolution.  We are creating the design `dsg` by using the FrF2 function. The arguments are the number of factors,  five, and the number of runs, eight. To view the design, we are going to use  the `summary` function. 
</div> 

So, this is a resolution III design, where main  factors are aliased to two-factor interactions, and the two-factor  interactions are aliased to each other. The alias structure shows exactly this.  The main factor A is aliased to BD and CE, the main factor B  with AD, C with AE, D with AB, and E with AC. And the two-factor interactions: BC with DE  and BE with CD. Finally, we have the design itself:  the combination of the low and high levels of the five factors A, B, C, D, and E.  

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 135843.png" HSPACE="10" VSPACE="10"/> 
</div>
Let's run it.  The output shows that the design has eight runs, as we have set.  The other important piece of information is the design generators. In this design,  D is equal to AB, and E is equal to AC. The identities of this design are ABD, ACE, and the combination between them: BCDE. 
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 140931.png" HSPACE="10" VSPACE="10"/> 
</div>
However, let's imagine we are not happy with having a resolution three design,  as the alias between main factors and two-factor interactions can hinder the analysis.  For this reason, we'd like to have at least a resolution IV design.  In our next design, we are going to use the number of factors and the design resolution  as parameters. It will result in the smallest possible fractional design.  So here we have the design dsg with the FrF2 function and the arguments are the number of  factors, five, and the design resolution, four. Let's run it.
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 142123.png" HSPACE="10" VSPACE="10"/> 
</div>
The output shows that we need at least 16 runs for a resolution IV design.  We have only one design generator, E equal to ABCD. This tells us two things:  First, this is a half-fraction design. And second, this is a resolution five design,  since the design identity, ABCDE, has five letters.
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 142413.png" HSPACE="10" VSPACE="10"/> 
</div>
The alias structure shows that there is no aliasing among main effects and two-factor interactions, as is expected for a resolution five design.
</div> 
<br>
And finally, we can see the design itself. The 16 runs are the combination of the low  and high levels of factors A, B, C, D, and E. However, how can we use this design outside R?  To view the design as a table, we can use the view function.  And here we have the design, now shown as a table and not in the console.  To export design, we can use the write.csv function.  But first, we need to set where we are going to save it.  To do it, we're going to click the tab files and select the folder where we would like to save.  I have mine already selected. Then we are going to click on the little gear on the right side,  and "set as working directory."  The arguments of the write.csv function are the object we are saving, in this case, the dsg,  and the name of the file. Let's run it.  Now we can see the design saved as a CSV file.  You can use MS Excel, MacOS Numbers, Google Sheets, or any other software  to open, edit, and write over it right. In our next lesson, we are going to look into  how to solve a highly fractionated design. Take care and see you shortly.  


