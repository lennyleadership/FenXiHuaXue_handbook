---
authors: David Gordon, edited by Lenny Lin
categories: null
date: "2022-06-20"
description: 
draft: false
lastmod: "2022-06-20"
series: null
tags: [Waters]
title: 5/7 Resolution
toc: true
---
Fundamentals of Mass Spectrometry provided by Waters (5 of 7)  

The definition of resolution is different for mass spectrometry with low resolution and for mass spectrometry with high resolution. 

This is a transcript of the following video.  


<iframe width="360" height="200" src="https://www.youtube.com/embed/qUhi98o1qUU?list=PL6yA4jv5tA-k9_2NVxm5jlzpZV_aW59DT" title="Fundamentals of MS (5 of 7) - Resolution" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!--more-->

Hello, my name is Dave, I work at Waters Corporation as a development scientist. I'm going to give a brief description of what is meant by the term resolution when it comes to mass spectrometry.  

Perhaps the most common usage of the term resolution relates to optical devices such as cameras or television screens. In that case, the resolution is often defined by the number of pixels the screen is made up of, which essentially is the definition of how detailed picture can be captured or displayed.  


## Unit Resolution
The premise is similar in mass spectrometry. Here the resolution is a measure of the ability to separate ions of one mass from those of another. So essentially, it's a measure of how detailed a spectrum the mass spec can generate. For low resolution mass spectrometers such as quadrupole instruments, the resolution is generally defined as <b>the full width of the peak at half its maximum height</b>, commonly abbreviated to `FWHM`. This value is set to approximately 0.7 amu and is not dependent on the mass being measured. So it sets this value for the whole mass range of the instrument. Using this resolution, it's possible to resolve one mass from the next integer mass. So for example, it'd be possible to distinguish mass 50 from mass 51 or mass 1000 from mass 1001. This is known as `unit resolution`.   


## High Resolution Definition
For high resolution mass spectrometry, a different measure is typically used. The International Union of Pure and Applied Chemistry defined the resolution of a mass spec in two ways, depending if overlapping peaks are present or not.   

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 150424.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<b>1)</b> If just a single peak is present, with no overlapping peaks, a singlet method is used. In this case, the resolution is expressed as the mass of the peak divided by the peak width at either 5 or 50% of the peak height.   

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 150703.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<b>2)</b> If more than one peak is present, and the peaks overlap, this makes the measurement of the peak width at 5% difficult. So in this case, a doublet method can be applied. Here, the resolution is measured using two overlapping peaks of approximately equal height, where the value between the peaks is at a given value, typically 10%. In this case, the resolving power is calculated as the mass of the second peak divided by the difference in mass between the peaks. Essentially, both of these calculations are a measure of the instruments ability to resolve ions of one mass from ions of an adjacent mass. But the singlet and doublet methods will result in different values for resolving power.  So it's important to know which method was used. 


## Application of Increased Resolution
Instruments with higher and higher resolution capabilities are being developed all the time. But what does increased resolution gives us? Well, as well as being better able to distinguish ions of different mass from each other. High resolution leads to <b>higher absolute mass accuracy</b>. This can be extremely beneficial.   

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 151256.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 151346.png" style ="float: left" HSPACE="10" VSPACE="10"/>
For example, on a low resolution instrument 2-octanone and naphthalene would essentially appear to be identical because the mass difference is less than 60 mili-daltons. However, as the resolution is increased, the peaks can be resolved from each other, and the accurate mass of each peak can be measured. That precision allows the potential molecular formula to be narrowed down to only a few possibilities. Not only does this improve the confidence to peak detected is the compound of interest, it also reduces the risk of contaminants interfering with the results. High resolution also allows analysis a very large complex compounds such as proteins, peptides, and oligosaccharides, because their tendency to form multiple charged ions, particularly through electrospray ionization. The ability to accurately identify the mass uncharged state of the detected peaks allows calculation of the actual mass of the compound. The combination of high resolution and high mass accuracy is a powerful tool in compound identification, structural elucidation, and research and discovery applications.