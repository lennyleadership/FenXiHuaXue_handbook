---
authors: null
categories: null
date: ""
description: 
draft: false
lastmod: "2022-03-17"
series: null
tags: null
title: Cross Talk
toc: true
---



<!--more-->

The low degree of crosstalk can be demonstrated by examining how long it takes to evacuate ions from the collision cell.   

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-03-17 173421.png"/>
<figcaption><b>Figure </b>: Collision cell clearing profile (500 pg Alprazolam, 20 ms dwell time)</figcaption>

The figure illustrates a sample analysis that is typically performed with an LC triple quad MS. The model is useful to show that the higher the mass of the compound moving through the triple quad, the longer it takes to evacuate the collision cell. For example, m/z 922 takes about 600 μsec to evacuate the collision cell using the linear potential, while m/z 118 only takes 350 μsec. This also demonstrates a low degree of crosstalk since the Y axis is logarithmic, showing complete clearance of the cell. This means that an inter-scan delay of 1 msec will be more than adequate to flush the collision cell of all ions.

[p42, Agilent 700A Triple Quadrupole GC/MS System: Concept Guide. rev2019](https://www.agilent.com/cs/library/usermanuals/public/user-manual-tq-gc-ms-7000-7010-series-concepts-guide-g7003-90052-en-agilent.pdf)
