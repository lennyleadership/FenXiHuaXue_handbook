---
authors: Scott Fredo, edited by Lenny Lin
categories: null
date: ""
description: 
draft: false
lastmod: "2022-06-19"
series: null
tags: [Waters]
title: Quadrupole Theory and Use
toc: true
---
LC-MS/MS Education Series 1/3 by Waters  

Operation modes: static mode, and scanning mode.

Acquisition modes: full scan, MRM, precursor ion scan, product ion scan, and neutral loss scan.

<iframe width="360" height="200" src="https://www.youtube.com/embed/iZH-oxP-OJ0" title="LC-MS/MS Education Series: Quadrupole Theory and Use" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<!--more-->

Hi, I'm Scott Freeto, and I'm a mass spec application specialist here at waters corporation. In today's video Quadrupole Theory and Use, I'm going to share some basic information about quadrupole mass spectrometers and their <mark>modes of operation</mark>.   

This video will help you to gain an understanding so that you'll have an appreciation of how we'll use the various modes to optimize the mass spec for the analysis of new compound or reoptimize an existing assay.  

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-19 225636.png" style ="float: left" HSPACE="50" VSPACE="50"/>
A quadrupole is the main element of a quadrupole mass spectrometer. A quadrupole assembly consists of four parallel rods equally spaced around the central axis. Single quadrupole mass spectrometers have one assembly while tandem quadrupole mass spectrometers have two assemblies separated by a collision cell. 

During the early days of quadrupole mass spectrometry, the collision cell was a quadrupole as well, resulting in three quadrupole assemblies in the mass spectrometer. That is why many scientists may refer to tandem quadrupole mass spectrometers as triple quadruples.  

Let's take a closer look at how a quadrupole works. Within the quadrupole assembly, a fluctuating field is created by applying RF and DC voltages to the quadrupole rods. Opposite rods have the same voltage is applied. This field affects the trajectory of ions traveling down the flight path between the rods based upon their mass to charge ratio. Each mass to charge ratio has an optimum RF DC setting, which creates a stable trajectory through the quadrupole. Thus, the quadrupole can be programmed so that only a specific mass to charge ratio is stable down the length of the quadrupole. Ions whose mass to charge is either too large or too small have an unstable flight path and ultimately strike the rods and are lost. Typically, a quadrupole can be operated in one of two ways, <mark>static or scanning</mark>. All acquisition modes are based on these two modes of operation.

<br>  
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-19 230332.png" style ="float: left" HSPACE="50" VSPACE="50"/>
In static mode, the RF and DC setting is set to only transmit the ion of interest and all other ions are lost. Thus, operating in static mode provides the highest sensitivity for the ion of interest, because the quadrupole spends the entire dwell time transmitting only the specified mass to charge ratio. Since only the selected mass to charge ratio is recorded, it is the only one observed in the mass spectrum rather than the multiple signals across the entire mass range as seen in a typical mass spectrum. This is the most common mode used in quantitative analysis. Since it is the most sensitive and additional information is not needed. On a single quad, this is called SR or selected ion recording. This mode may also be called <mark>SRM or selected ion monitoring</mark>.  

<br>  
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-19 230545.png" style ="float: left" HSPACE="50" VSPACE="50"/>
In scanning mode, the RF and DC settings are ramped over time to create the typical mass spectrum. Ions are only transmitted to the detector when the RF and DC setting is correct to allow stable motion for that particular mass to charge ratio. The scan time is the amount of time the quadrupole spends scanning the entire mass range from the start mass to the end mass. Thus, if the mass spectrometer scans at 10,000 Dalton's per second and the mass ranges from 200 to 1200 Daltons or a difference of 1000 Daltons, the scan time is point one seconds, this is called <mark>Full Scan mode</mark>. This mode provides the most information about all the ions in your sample. However, it is not as sensitive as selected ion monitoring, because the quadrupole transmits each mass to charge ratio for only a small percentage of the total scan time.   

<br>  
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-19 230941.png" style ="float: left" HSPACE="50" VSPACE="50"/>
Sometimes, when working with a tandem quadrupole instrument, we talk about doing MS or MSMS acquisitions.  An MS acquisition is when we set just one of the quadruples to either static or scanning mode while the other quadrupole is set with an RF voltage only and no DC voltage. When in this mode, the quadrupole will allow all ions to pass through without affecting them. The other characteristic of an MS experiment is that the collision cell is set to also pass all ions through without fragmentation.  An MSMS experiment is one where each quadrupole is set to either static or scanning mode. And if adequate collision energy is imparted to the collision cell, fragmentation will occur.   

<br>  
<div class="row">
  <div class="column">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-19 231422.png"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-19 231817.png"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-19 231624.png"/>
  </div>
  <div class="column">
The quads in an MSMS acquisition can be set as scanning or static, allowing us to acquire data in several different modes.
  </div>
</div> 

<style type = "text/css">
/* image and text side-by-side */
* {
  box-sizing: border-box;
}

.row {
  margin-left:-5px;
  margin-right:-5px;
}
  
.column {
  float: left;
  padding: 5px; /* space between two tables*/
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}

/* end of the setting for two tables side-by-side */
</style>


  

<br>  
<br>  
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-19 231941.png" style ="float: left" HSPACE="50" VSPACE="50"/>
The most common acquisition mode using a tandem quad however is known as MRM. Multiple reaction monitoring where both quads are set to static mode. This is the most common way to use a tandem quad because it is the most sensitive mode for quantitative analysis. The first quadrupole will pass only the precursor or intact form of the analyte while the second quadrupole is set to pass a specific fragment of the analyte that was generated in the collision. 

So, I hope you found this information on quadrupole theory and use to be helpful and informative. To review, quadrupole assemblies are a set of four parallel rods that work together to control the trajectory of ions in the mass spectrometer. A fluctuating field is generated inside the quadrupole by applying RF and DC voltages to the quadrupole rods. The path of the ion through the field is based upon its mass to charge ratio. Quadruples can be static with the RF and DC settings are optimized to transmit only the mass to charge ratio of interest allowing only those ions through the mass spectrometer. 
And lastly, they can also scan where the RF and DC voltage settings are ramped to let ions through the quadrupole in order of increasing mass to charge ratio. A wide range of acquisition modes such as full scan, MRM precursor ion scan, product, ions scan, and neutral loss scan are available on tandem quad mass spectrometers. 

I hope you found this video useful. Learn more about waters LCMS solutions in the clinical laboratory at waters.com/clinical.