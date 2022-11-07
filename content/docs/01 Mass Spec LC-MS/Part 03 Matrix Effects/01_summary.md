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
  <img width = "360" src = "/docs/images/Screenshot 2022-10-15 214516.png"/>
  <figcaption class = "bottom"><b>Figure 1</b>. General set-up for identifying matrix effect: postcolumn infusion of compound while injecting extracted blank</figcaption>
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
<b><font class = "font_upper">Drawback</font></b>. This approach can only be feasible when the sensitivity of the assay is very high <a href="#ref">[4]</a>. It will raise the limit of quantitation, which could affect the required sensitivity <a href="#ref">[1]</a>.  

2) Remove interfering compounds from samples <a href="#ref">[1,5,6,7,8]</a>.   
<b><font class = "font_upper">Drawback</font></b>. Most of the sample cleanup methods fail to remove impurities that are similar to the analyte and, hence, likely to be coeluted with the analyte <a href="#ref">[9, 10]</a>.

3) Change chromatographic parameters to avoid coelution of analytes and interfering compounds <a href="#ref">[11]</a>.  
<b><font class = "font_upper">Drawback</font></b>. Modifying chromatographic conditions can be time-consuming, and some of the additives used in the mobile phase to improve separation have been found to suppress the electrospray signal of the analytes (3,4,9,15) <a href="#ref">[12,11,6,13]</a>. Furthermore, even when the sample is devoid of coeluted substances, trace impurities present in the mobile phase can significantly suppress the analyte peak (19).

4) Change MS conditions to reduce the occurrence of matrix effects in the ion source <a href="#ref">[3]</a>.

5) The rectification of data  
(i) the external-matched standards method <a href="#ref">[1]</a>  
Analytical standards are fortified in a sample extract that has been treated exactly the same as the regular sample and is free of the residues of interest <a href="#ref">[1]</a>.   
<b><font class = "font_upper">Drawback</font></b>. The matrix-matching technique requires many blank matrices and appropriate blank matrices are not always available for the preparation of external standards (9,11,18,23) <a href="#ref">[6,9,10,14]</a>.  It is also impossible to match the matrix of the calibration standards with each of the samples exactly, as each sample has coeluting, interfering compounds that are thereby exposed to a different extent of ionization suppression (18) <a href="#ref">[10]</a>.

&emsp;(ii) the echo-peak technique   
&emsp;<b><font class = "font_upper">Drawback</font></b>. Echo-peak does not compensate for matrix effects completely because both standard and analyte peaks are not eluted at the exact same retention time (11) <a href="#ref">[9]</a>.  

&emsp;(ii) the internal standard method <a href="#ref">[1,3]</a>  
&emsp;<b><font class = "font_upper">Drawback</font></b>. The stable isotope–labeled internal standards (SIL-IS) approach is the best available option but it is expensive and standards are not always commercially available for the analyte of interest (4,9,23) <a href="#ref">[11,6,14]</a>.

6) Standard addition method <a href="#ref">[1,3]</a>  
<b><font class = "font_upper">Drawback</font></b>. Firstly, the approximate concentration of the analyte must be known to construct a proper calibration curve. Secondly, it requires at least three more additional sample runs per sample in order to have sufficient data points for the calibration curve <a href="#ref">[1]</a>.

7) Change from ESI to APCI <a href="#ref">[1]</a>


## Reference  
<p id="ref">[1] <a href = "https://www.chromatographyonline.com/view/important-considerations-regarding-matrix-effects-when-developing-reliable-analytical-residue-method" target="_blank" rel="noopener noreferrer">LC/GC: Important Considerations Regarding Matrix Effects When Developing Reliable Analytical Residue Methods Using Mass Spectrometry</p>  

<p id="ref">[2] <a href = "https://cdn.sanity.io/files/0vv8moc6/biopharn/1a7e564988c4ca05949add7061339d9dadbe47ec.pdf/article-7275.pdf" target="_blank" rel="noopener noreferrer">Systematic Troubleshooting for LC/MS/MS - Part 2: Large-Scale LC/MS/MS and Automation</a></p>

<p id="ref">[3] <a href = "https://www.chromatographyonline.com/view/strategies-detection-and-elimination-matrix-effects-quantitative-lc-ms-analysis" target="_blank" rel="noopener noreferrer">LC/GC: Strategies for the detection and elimination of matrix effects in Quantitative LC-MS Analysis</a></p>

<p id="ref">[4] C. Ferrer, A. Lozano, A. Agüera, A.J. Girón, and A.R. Fernández-Alba, <i>J. Chromatogr.</i> <b>A 1218</b>, 7634 (2011).</p>

<p id="ref">[5] (1) E. Chambers, D.M. Wagrowski-Diehl, Z. Lu, and J.R. Mazzeo, <i>J. Chromatogr. B</i> <b>852</b>, 22 (2007).</p>

<p id="ref">[6] (9) H. Trufelli, P. Palma, G. Famiglini, and A. Cappiello, <i>Mass Spectrom. Rev.</i> <b>30</b>, 491 (2011).</p>

<p id="ref">[7] (10) R. Bonfiglio, R.C. King, T.V. Olah, and K. Merkle, <i>Rapid Commun. Mass Spectrom.</i> <b>13</b>, 1175 (1999).</p>

<p id="ref">[8] (13) C.R. Mallet, Z. Lu, and J.R. Mazzeo, <i>Rapid Commun. Mass Spectrom.</i> <b>18</b>, 49 (2004).</p>

<p id="ref">[9] (11) H. Stahnke, S. Kittlaus, G. Kempe, and L. Alder, <i>Anal. Chem</i>. <b>84</b>, 1474 (2011).</p>

<p id="ref">[10] (18) A.K. Hewavitharana, <i>J. Chromatogr</i>. <b>1218</b>, 359 (2011).</p>

<p id="ref">[11] (4) D.A. Volmer, <i>LCGC North Am</i>. <b>24</b>, 498 (2006).</p>

<p id="ref">[12] (3) P.J. Taylor, <i>Clin. Biochem</i>. <b>38</b>, 328 (2005).</p>

<p id="ref">[13] (15) F. Gosetti, E. Mazzucco, D. Zampieri, and M.C. Gennaro, <i>J. Chromatogr</i>. <b>A1217</b>, 3929 (2010).</p>

<p id="ref">[14] (23) M. Stüber and T. Reemtsma, <i>Anal. Bioanal. Chem</i>.  <b>378</b>, 910 (2004).</p>

<p id="ref">[15] </p>