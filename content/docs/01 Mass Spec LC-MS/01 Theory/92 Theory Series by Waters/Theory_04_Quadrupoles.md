---
weight: 1
title: Quadrupoles
authors: David Gordon, edited by Lenny Lin
categories: null
tags: [Waters]
description: 
draft: false
date: "2022-06-20"
lastmod: "2022-06-20"
series: null
toc: true
---

Fundamentals of Mass Spectrometry provided by Waters (4 of 7)  

A quadruploe consists of four parallel rods arranged around the central axis.  

Static potentials or DC voltages, and alternating potentials or RF voltages are applied to the quadrupole rods with one pair of rods having the opposite polarity to the other pair.  These voltages create a fluctuating electric field between the rods.  

Different ions can pass through the quadrupole and won't strike rods under different ratios of the RF and DC voltages.  As the the DC to RF ratio is increased linearly with time, the ions of that particular mass are transmitted through the quadrupole to the detector.  

This is a transcript of the following video.  


<iframe width="360" height="200" src="https://www.youtube.com/embed/6_mavZ_WKoU?list=PL6yA4jv5tA-k9_2NVxm5jlzpZV_aW59DT" title="Fundamentals of MS (4 of 7) - Quadrupoles" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!--more-->
---

Hello, my name is Dave, I work at Waters corporation as a development scientist, I'm going to give a brief overview of what a quadrupole is and how it works.  

## Structure
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 125101.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 125142.png" style ="float: left" HSPACE="10" VSPACE="10"/>
So a quadrupole is a mass analyzer, and it consists of four parallel rods arranged around the central axis as shown. Static potentials or DC voltages, and alternating potentials or RF voltages are applied to the quadrupole rods with one pair of rods having the opposite polarity to the other pair. These voltages create <b>a fluctuating electric field between the rods</b>. The field oscillates as shown, typically at frequencies of approximately one megahertz.    

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 125310.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<br>   
The stability of an ion when passing through this field is dependent on <b>the mass to charge ratio of the ion</b>. Since the voltage is defined the field and we control the voltages that can be set such that only a single mass to charge ratio is stable and can pass down the length of the quadrupole. Ions whose mass to charge ratio is too large or too small, have unstable motion.  They strike the quadrupole rods and therefore aren't detected. The ion motion within a quadrupole is relatively complex, so we won't go into details here. It's possible to plot ratios of the RF and DC voltages for which the ion motion does not extend beyond the inscribed radius of the rods in the X and the Y axis. In other words, we can derive ratios where the ion motion is stable.    
<br>   

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 125507.png" style ="float: left" HSPACE="10" VSPACE="10"/>
So plotting this gives the following. Obviously, for an ion to make it through the quadrupole it needs to be stable in both the x and y axis. And from this plot, we can see that there are several regions where the stability zones overlap. But all commercial quadruples use what's called the first stability region, mainly because this is where the voltage requirements are the lowest.   
<br> 

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 125702.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 125806.png" style ="float: left" HSPACE="10" VSPACE="10"/>
If we look closer at this region, we can see it has the following shape. The stability region is dependent on the mass to charge ratio of the ion. So if we plot the stability regions of different masses on a single axis, we get the following. Typically, when scanning with a quadrupole, the RF and DC are ramped linearly with time.  As the voltages are increased, the scan line cuts through the stability regions of different masses, and the ions of that particular mass are transmitted through the quadrupole to the detector. A plot can then be created as signal versus time, which is translated into a plot of signal versus mass, or in other words, a <b>mass spectrum</b>. We're able to resolve the masses from each other because the scan line doesn't cross two stable regions at the same time. We can also increase the DC to RF ratio to the point where the scan line crosses the very tips of disability regions. As you can see, as we do that, the peak widths are reduced. Therefore the resolution is increased.  
<br>  

As we attempt to operate a quadrupole at higher and higher resolution, the transmission reduces because the entry conditions become more and more stringent. In other words, the ions must enter closer and closer to the central axis to make it through. The theoretical limit of the resolution of the quadrupole relates to the number of cycles of RF the ion is exposed to. So increasing the frequency of the RF, making the quadrupole longer or slowing the ions down will increase the theoretical maximum. However, there are practical limitations to the resolution performance of quadruples, which are dominated by the mechanical accuracy of the quadrupole itself.   

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 130001.png" style ="float: left" HSPACE="10" VSPACE="10"/>
Because of this, quadruples are generally operated with a resolution set to what is known as unit resolution, this is the point at which ions with a mass difference of one amu can be resolved from each other.  


[Other source: Azo: Using Graphical Tools to Understand Quadrupole Theory](https://www.azom.com/article.aspx?ArticleID=10996)  
[Other source: Shimadzu: Peak Width and Mass Scan Line](https://www.shimadzu.com/an/service-support/technical-support/gas-chromatograph-mass-spectrometry/analysis-results/mass_peak/overview.html)
