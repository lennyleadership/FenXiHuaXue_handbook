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
Matrix effects are either observed as suppression or enhancement of analyte signal in the electrospray ionization (ESI) source <a href="#ref">[1]</a>.  GC-MS is also subject to matrix effects <a href="#ref">[1]</a>.


## What cause matrix effects?
Unwanted compounds compete with analytes for ionization <a href="#ref">[2]</a>.


## How to assess it?

### Postcolumn infusion
<div class = "quote">
&emsp;A useful method to assess matrix suppression is `postcolumn infusion` of an analyte into the MS detector. The extracted blank matrix is injected by an autosampler onto the analytical column. The setup is shown in <b>Figure 1</b>. The purpose of postcolumn infusion with analyte is to raise the background level so that the suppression matrix will show as negative peaks. This setup has been successfully used to identify and troubleshoot matrix suppression peaks <a href="#ref">[2]</a>.  

<figure>
  <img width = "540" src = "/docs/images/Screenshot 2022-10-15 214516.png"/>
  <figcaption><b>Figure 1</b>. General set-up for identifying matrix effect: postcolumn infusion of compound while injecting extracted blank</figcaption>
</figure>
</div>

<br>
<div class = "quote">
&emsp;The postcolumn infusion method assesses matrix effects <u>qualitatively</u>. A constant flow of analyte is infused into the HPLC eluent, followed by injection of the blank sample extract. A variation in signal response of the infused analyte caused by coeluted interfering compounds indicates ionization suppression or enhancement <a href="#ref">[3]</a>.  

Identify the retention time region(s) where matrix effects were observed firstly, then adjust the chromatography condition to prevent analyte elution from from these regions.  

<b><font class = "font_upper">Drawback</font></b>. The process of postcolumn infusion is time consuming and requires additional hardware, and it is not appropriate for multianalyte samples <a href="#ref">[3]</a>. 
</div>

### Postextraction spike
<div class = "quote">
&emsp;The postextraction spike method evaluates matrix effects by comparing the signal response of an analyte in neat mobile phase with the signal response of an equivalent amount of the analyte in the blank matrix sample spiked post-extraction <a href="#ref">[3]</a>.  

<b><font class = "font_upper">Drawback</font></b>. For endogenous analytes such as metabolites (for example, Creatinine) blank matrix (urine or plasma) is not available <a href="#ref">[3]</a>.
</div>

## How to correct it?

1) Dilute and shot  
<b><font class = "font_upper">Drawback</font></b>. this approach can only be feasible when the sensitivity of the assay is very high <a href="#ref">[4]</a>.  

2) Remove interfering compounds from samples <a href="#ref">[5,6,7,8]</a>.

3) Change chromatographic parameters to avoid coelution of analytes and interfering compounds.

<b><font class = "font_upper">reference</font></b>: 
<p id="ref">[1] <a href = "https://www.chromatographyonline.com/view/important-considerations-regarding-matrix-effects-when-developing-reliable-analytical-residue-method" target="_blank" rel="noopener noreferrer">LC/GC: Important Considerations Regarding Matrix Effects When Developing Reliable Analytical Residue Methods Using Mass Spectrometry</p>  

<p id="ref">[2] <a href = "https://cdn.sanity.io/files/0vv8moc6/biopharn/1a7e564988c4ca05949add7061339d9dadbe47ec.pdf/article-7275.pdf" target="_blank" rel="noopener noreferrer">Systematic Troubleshooting for LC/MS/MS - Part 2: Large-Scale LC/MS/MS and Automation</a></p>

<p id="ref">[3] <a href = "https://www.chromatographyonline.com/view/strategies-detection-and-elimination-matrix-effects-quantitative-lc-ms-analysis" target="_blank" rel="noopener noreferrer">LC/GC: Strategies for the detection and elimination of matrix effects in Quantitative LC-MS Analysis</a></p>

<p id="ref">[4] C. Ferrer, A. Lozano, A. Agüera, A.J. Girón, and A.R. Fernández-Alba, *J. Chromatogr.* **A 1218**, 7634 (2011).</p>


