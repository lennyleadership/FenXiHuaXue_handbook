---
weight: 1
title: Summary of Matrix Effects
authors: null
categories: ["Matrix Effects in LC-MS/MS"]
tags: null
description:  
draft: false
date: "2022-11-07"
lastmod: "2022-11-07"
series: null
toc: true
---



<!--more-->
---

## What is matrix effects?
Matrix effects are either observed as suppression or enhancement of analyte signal in the electrospray ionization (ESI) source <a href="#section 1">[1]</a>.  GC-MS is also subject to matrix effects <a href="#section 1">[1]</a>.


## What cause matrix effects?
Unwanted compounds compete with analytes for ionization <a href="#section 2">[1]</a>.


## How to assess it?

<div class = "quote">

&emsp;The matrix effect is determined by comparing peak areas of neat solutions spiked (postextraction) into blank matrix with those of other neat solutions. Because the analytes are not extracted, the analyte should have the same response in postextraction spiked samples and in neat solutions. The matrix ingredients, therefore, cause whatever differences are noted in the responses.

&emsp;A useful method to assess matrix suppression is `postcolumn infusion` of an analyte into the MS detector. The extracted blank matrix is injected by an autosampler onto the analytical column. The setup is shown in <b>Figure 1</b>. The purpose of postcolumn infusion with analyte is to raise the background level so that the suppression matrix will show as negative peaks. This setup has been successfully used to identify and troubleshoot matrix suppression peaks.  

<figure>
  <img width = "540" src = "/docs/images/Screenshot 2022-10-15 214516.png"/>
  <figcaption><b>Figure 1</b>. General set-up for identifying matrix effect: postcolumn infusion of compound while injecting extracted blank</figcaption>
</figure>
</div>

## How to correct it?


<b><font class = "font_upper">reference</font></b>: 
<p id="section 1">[1] 
<a href = "https://www.chromatographyonline.com/view/important-considerations-regarding-matrix-effects-when-developing-reliable-analytical-residue-method" target="_blank" rel="noopener noreferrer">LC/GC: Important Considerations Regarding Matrix Effects When Developing Reliable Analytical Residue Methods Using Mass Spectrometry</p>  

<p id="section 2">[1] <a href = "https://cdn.sanity.io/files/0vv8moc6/biopharn/1a7e564988c4ca05949add7061339d9dadbe47ec.pdf/article-7275.pdf" target="_blank" rel="noopener noreferrer">Systematic Troubleshooting for LC/MS/MS - Part 2: Large-Scale LC/MS/MS and Automation</a></p>
