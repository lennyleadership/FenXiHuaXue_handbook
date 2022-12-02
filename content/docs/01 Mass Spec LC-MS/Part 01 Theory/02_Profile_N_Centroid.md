---
weight: 2
title: Centroid or Profile
authors: Lenny Lin
categories: null
tags: [MS]
description: 
draft: false
date: "2022-05-14"
lastmod: "2022-10-17"
series: null
toc: true
---



<!--more-->
---

## What are Profile and Centroid MS data?
MS data collected off an instrument is presented as either profile or centroid mode. Shown below are two mass spectra illustrating an ion cluster for profile data and a centroid mass spectrum created from the profile data.

In profile mode, a peak is represented by a collection of signals over several scans. The advantage of profile data is it is easier to classify a signal as a true peak from noise off the instrument.

In centroid mode, the signals are displayed as discrete m/z with zero line widths. The advantage of centroid data is the file size is significantly smaller as there is less information describing a signal.  

<figure>
<img width ="360" height= "200" src = "/docs/images/profile2.gif"/>  
<figcaption><a href ="https://blog.acdlabs.com/elucidation/2008/03/what-is-the-dif.html">Source</a>
</figcaption>
</figure>

## What are Profile and Centroid MS data? (2)
1) Profile means the continuous wave form in a <mark class = "lemon">mass spectrum</mark>.   
• Data is a continuous wave form.  
2) Centroid means the peaks in a profile data is changed to bars.  
• m/z values are discrete.  
• location of the bar is center of the profile peak.  
• height of the bar is area of the profile peak. 

