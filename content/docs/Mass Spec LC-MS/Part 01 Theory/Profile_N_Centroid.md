---
authors: Lenny Lin
categories: null
date: ""
description: 
draft: false
lastmod: "2022-05-14"
series: null
tags: [MS]
title: Centroid or Profile
toc: true
---



<!--more-->

## What are Profile and Centroid MS data?
MS data collected off an instrument is presented as either profile or centroid mode. Shown below are two mass spectra illustrating an ion cluster for profile data and a centroid mass spectrum created from the profile data.

In profile mode, a peak is represented by a collection of signals over several scans. The advantage of profile data is it is easier to classify a signal as a true peak from noise off the instrument.

In centroid mode, the signals are displayed as discrete m/z with zero line widths. The advantage of centroid data is the file size is significantly smaller as there is less information describing a signal.  

<img width ="720" height= "400" src = "/docs/images/profile2.gif"/>
<a href ="https://blog.acdlabs.com/elucidation/2008/03/what-is-the-dif.html">Source</a>

## What are Profile and Centroid MS data? (2)
1) Profile means the continuous wave form in a <mark>mass spectrum</mark>. 
• Data is a continuous wave form.  
2) Centroid means the peaks in a profile data is changed to bars.  
• m/z values are discrete.  
• location of the bar is center of the profile peak.  
• height of the bar is area of the profile peak. 

