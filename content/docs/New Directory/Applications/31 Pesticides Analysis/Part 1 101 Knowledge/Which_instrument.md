---
authors: Lenny Lin
categories: null
date: "2022-06-24"
description: 
draft: false
lastmod: "2022-06-24"
series: null
tags: null
title: Which Instrument?
toc: true
---

Which chromatography and mass spectrometry systems are best for pesticide analysis?


<!--more-->

## Thermo Pesticide Residue Analysis
<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-06-26 141901.png"/>

<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-06-26 142026.png"/>

HRAM: High resolution accurate mass



## Capabilities of the Different Analyzers for Pesticide Residue Analysis <a href="#ref">[1]</a>

<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-06-26 225310.png"/>




## Choose GC-MS or LC-MS for Pesticide Analysis

### Sample Introduction

**GC**: An important issue when selecting an injector is the properties of the analyte, such as potential for chemical instability, thermal degradation, or discrimination of high-boiling-point compounds within the injector. A number of problematic pesticides are prone to degradation in the GC injector, including phthalimide fungicides (e.g., captan), organochlorines (e.g., DDT and chlorothalonil), organophosphorus pesticides (*e.g.*, dimethoate), and pyrethroids.  The major source of inaccuracy in pesticide residue analysis by GC-MS, especially with food, is related to the injection of coextractives from the sample, the so-called "matrix effect".  A buildup of coextractives in a GC inlet may lead to successive adverse changes in the performance of the chromatographic system such as the loss of analytes and peak tailing due to undesired interactions with active sites in the inlet and column. Analytes that give poor peak shapes or degrade have higher detection limits, are more difficult to identify and integrate, and are more prone to interferences than stable analytes that give narrow peaks. For susceptible analytes, significant improvements in peak quality are obtained when matrix components are present because they fill active sites, thus reducing analyte interactions. However, this can lead to problems with quantification. These matrix effects can produce an overestimation of the analyte concentration if calibration has been performed with standards in solvent. The presence of matrix effects should be evaluated for all tested analytes. There are a number of approaches for preventing, reducing, or compensating for the occurrence of matrix effects including the use of matrix-matched calibrants, which is recommended for the monitoring of pesticide residues within the European Union. 

**HPLC**: no thermal degradation, very few surface activity issues, can do large-volume injection for lower detection limits.  

With LC-MS/MS, sample clean-up is less crucial when compared with analysis by GC-MS/MS.


### Chromatography

**GC**:

**HPLC**:
HPLC can eliminate isobaric interferences and matrix effects that may affect the relative response of analytes.  

Ion suppression is observed either from coelution with other analytes or, more likely, coeluting matrix components.

Reversed-phase columns are widely used for detection of pesticide residues.


### Mass Spectrometry

<table style="width:100%;">
<caption style="text-align:left", align = "top"><b>Mass Spectrometry</b></caption>
<colgroup><col style="width: 40%" /><col style="width: 60%" />
</colgroup>
<thead>
  <tr VALIGN=TOP class="header">
    <th><p>GC-MS</p></th>
    <th><p>LC-MS</p></th>
  </tr>
</thead>
<tbody VALIGN=TOP>
  <tr class="odd">
    <td><p>sentence left
    </p></td>
    <td><p>
    </p></td>
  </tr>
  <tr class="even">
    <td><p>sentence left
    </p></td>
    <td><p> sentence right.
    </p></td>
  </tr>
</tbody>
</table>

LC-MS:  
single quadrupole instruments are rarely used now for pesticide residue analysis, as, when combined with API sources, the technique lacks the selectivity required for both detection in complex matrices and for confirmation of identity. Single quadrupole MS has been superseded by MS/MS.   

LC-MS/MS with a triple quadrupole instrument in MRM mode is currently the most widely used technique for the quantification of target pesticides as it delivers the sensitivity required for monitoring compliance with the legislation. The use of other modes, such as neutral loss or precursor ion scanning, is limited by poor sensitivity and specificity.   

## Choose Mass Spectrometer

### MS/MS
One of the current challenges for LC-MS/MS is to be able to acquire sufficient data points for quantification while acquiring an ever increasing number of MRM transitions, with very short dwell times (e.g., 5 ms), especially when coupled with UPLC.  

The main limitation of triple quadrupoles in MRM mode is that confirmation of identity is based on the ratio of one or more MRM transition rather than full MS/MS product ion spectra. The replacement of Q3 in a QqQ instrument with a scanning LIT enhances its sensitivity in product ion scanning mode. Additionally, the system has MS<sup>3</sup>  capability and time-delayed fragmentation scans that aid structure elucidation. Quantitative (MRM) and qualitative (MS/MS or MS<sup>3</sup> product ion spectra) work can be performed concomitantly on the same instrument. Although reports of the use of the QqLIT instrument for pesticide residue analysis are currently limited to material from the vendor it is in routine use in some laboratories.     

As the lists of targeted compounds get longer, setting up time-segmented MRM
methods becomes more and more complicated.  

Matrix effects are the major problem of LC-MS/MS <a href="#ref">[2]</a>.


### ToF and Other Mass Spectrometer
High resolution and accurate mass are available from four types of instruments: double-focusing magnetic sector, LIT-Orbitrap, FT-ICR, and TOF mass spectrometers.  

The current trend in pesticide residue analysis is to use LC-TOF MS or LC-QTOF MS systems because they are easier and less expensive to operate compared with the other three mass spectrometers.  

Although TOF-MS can record accurate full spectral information with good sensitivity, this is of limited use unless resolution and mass accuracy are enhanced, as the spectra generated using the soft ionization API interfaces are usually characterized by a lack of fragment ions.   

LC-TOF instruments are capable of a resolving power of 10,000–20,000 (FWHM) and an accuracy of 2–5 ppm and the rapid acquisition rate combines well with fast chromatography systems. 

TOF was found to be around one order of magnitude less sensitive than a triple quadrupole instrument used in SRM mode and so sensitivity of LC-TOF may not always be sufficient for the intended application.  

Although acquisition rates have now improved (e.g., 20 spectra/s) and issues related to linear range still hamper the use of LC-TOF for quantification, some recent success has been reported.  

<div class="row">
  <figure>
    <img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-29 132505.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<figcaption><b>Figure </b>: Schematic overview of a QTOF mass spectrometer</figcaption>
  </figure>
</div>

The development of the hybrid quadrupole–time-of-flight (QTOF) instruments presents the analyst with all the advantages indicated for the LC-TOF with the additional capability of accurate mass product ion scans.  When confirming positive findings, both the exact masses and the relative intensities of all the product ions can be compared with those of the reference standard. The enhanced selectivity of MS=MS, when combined with high resolution and mass accuracy of the measurement of the product ions, provides low chemical background and hence improved quality of confirmation.  The LC-QTOF has been used for the elucidation of pesticide metabolites and transformation products, but the potential is more limited when no previous knowledge is available.  In such cases, the most common approach is to search a database for the molecular formula. The accurate product ion mass spectrum provides additional structural information, which can be used for comparative purposes with reference standards or to distinguish between isomers.


## Analytical Techniques:
<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-01 103432.png"/>
<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-01 103639.png"/>
<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-01 104013.png"/>
<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-01 104043.png"/>
<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-01 104122.png"/>
<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-01 104150.png"/>
<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-01 104307.png"/>

LC–MS/MS was shown to be better suited for sulfonyl or benzoyl ureas, carbamates, and triazines than GC–MS. For the remainder pesticides, the application scope of LC–MS/MS was also wider than that of GC–MS. Both GC–MS and LC–MS based methods revealed a significant variation in sensitivity, covering at least a range of 3–4 orders of magnitude, depending on the pesticide analyzed. However, a comparison of the median of MDLs clearly showed much higher sensitivity if determinations were based on LC–MS/MS. The better performance of LC–MS/MS is probably determined by several reasons. Among them the larger injection volume used in LC–MS/MS (20 mL vs. 1 mL) and the lower amount of fragmentation during ionization (ESI vs. EI) may explain some of these differences.<a href="#ref">[3]</a> 

<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-01 121313.png"/>

### Gas Chromatography
The choice of analytical technique used for the detection of pesticides is strongly dependent on the analyte’s polarity. Compounds with high log Kow, such as OCs, Py, and most OPs, are nonpolar and are preferably analyzed by gas chromatography (GC), while polar compounds such as carbamates, benzimidazoles, and some OPs are amenable by liquid chromatography (LC).  

<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-01 111245.png"/>
<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-01 111814.png"/>


### Liquid Chromatography
Although LC is the method of choice for thermally labile, ionic, and polar compounds, such as carbamates, urea, and phenoxy herbicides or benzimidazoles, it has been less applied than GC.

## Misc
Currently, triple quadrupole (QqQ) is the first choice for pesticide residue analysis in routine laboratories using gas chromatography (GC) and liquid chromatography (LC) systems (Go´mez-Ramos, Ferrer, Malato, Agu¨era, & Ferna´ndez-Alba, 2013).  

Most of screening methods used in routine laboratories detect the presence of
pesticides as a pretarget screening (previously known compounds) by lowresolution mass spectrometry instruments, such as single quadrupole (Jedziniak, Szprengier-Juszkiewicz, & Olejnik, 2009), QqQ (Martı´nez-Vidal, Garrido-Frenich, Aguilera-Luiz, & Romero-Gonza´lez, 2010), and ion trap analyzers (Smith, Gieseker, Rimschuessel, Decker, & Carson, 2009), applying different scan modes. <a href="#ref">[4]</a> 

## References:
<p id="ref">[1] Analysis of Pesticides in Food and Environmental Samples, Jose L. Tadeo</p>
<p id="ref">[2] LC-MS/MS in forensic toxicology: What about matrix effects?, Jan, 2011, Ruth Verplaetse</p>
<p id="ref">[3] p251, Analysis of Pesticides in Food and Environmental Samples, CRC Press, 2008, edited by Jos&eacute; L. Tadeo</p>
<p id="ref">[4] p132, Applications in High Resolution Mass Spectrometrey Food Safety and Pesticide Residue Analysis, edited by Roberto Romero-Gonz&#225;lez, &copy;2017 ELSEVIER.</p> 

p83, Analysis of Pesticides in Food and Environmental Samples, CRC Press, 2008, edited by Jos&eacute; L. Tadeo


<style type = "text/css">

.row {
  margin-left:-5px;
  margin-right:-5px;
}

.row::after {
  content: "";
  clear: both;
  display: table;
}

figure {
  text-align: left;
  font-style: italic;
  font-size: smaller;
  text-indent: 0;
  margin: 0.5em;
  padding: 0.5em;
}

</style>
