---
authors: edited by Lenny Lin
categories:
date: "2022-06-28"
description:
draft: false
lastmod: "2022-07-01"
series: 
tags: []
title:  Ion Trap Quadrupole
toc: true
---

series: [Analysis of Pesticides in Food and Environmental Samples, edited by Jose L. Tadeo]

## Summary
Ion trap works at unit mass resolution, selectivity is limited.

Advantage:  
) selectively store ions of one `mass-to-charge` value.  As a result, the sensitivity is increased.  
) When coupling with CID and a quadrupole, ion trap can store one precursor ion.

Disadvantage:  
) 


<!--more-->


## What is ion trap quadrupole? <a href="#ref">[1]</a>
The principle of the trap is to store the ions in a three-dimensional quadrupole field.  

<div class = "row">
  <figure>
    <img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-27 124521.png" style ="float: left" HSPACE="10" VSPACE="10"/>
    <figcaption><b>Figure </b>: Schematic overview of a three-dimensional quadrupole ion-trap mass spectrometer</figcaption>
  </figure>
</div>

Ions are removed one `m/z value` at a time by resonant ejection to obtain a scan recorded as a mass spectrum.  

Ions can be formed internally and stored as they are formed or externally followed by injection and storage.   

The ability to <mark>selectively store ions</mark> provides a substantial improvement in sensitivity when compared with a quadrupole instrument when recording mass spectra and so permits the recording of complete mass spectra in concentration ranges in which quadrupole instruments have historically had to operate in SIM mode.  

This aspect is particularly advantageous for pesticide residue analysis when the components under investigation are present in the sample only in very small concentrations and an unambiguous identification is required.   

Moreover, no selection of characteristic ions is necessary during data acquisition for MS with a 3D QIT, permitting investigation of unknown samples, that is, screening of samples on the basis of complete mass spectra. Thus, <mark>substances that were not originally sought can be detected by revisiting the data</mark>. This is not possible in the case of the SIM technique, which operates on the principle of the selection of previously known substance and characteristic ions.   

## GC single ion trap MS <a href="#ref">[2]</a>
Disadvantages of GC-MS using original 3D QITs were related to space charge problems, leading to lower mass resolution and mass shifts and ion/molecule reactions called "self-CI."  Although modern instruments have various techniques to prevent overfilling of the trap, this can still be a problem when analyzing pesticides at low levels in dirty matrices because the trap is filled with ions derived from matrix leaving little space for the small number of analyte ions. The limited storage of ions has also limited the dynamic range of the 3D QIT. 

## Ion trap vs. single quadrupole <a href="#ref">[2]</a>
Both single quadrupole and 3D QIT work at <mark>unit mass resolution</mark>, selectivity is limited, so these instruments can suffer from reduced sensitivity due to the contribution to the analyte signal from chemical noise.

## IOn trap tandem MS <a href="#ref">[3]</a>
The capability of the 3D QIT to <mark>store ions of a single m/z value</mark> to the exclusion of ions of all other m/z values allows for MS/MS by means of collision-induced dissociation (CID) within a single mass analyzer. An ion can be stored as a precursor, and that stored ion can then be manipulated to collide with the cooling gas molecules to produce product ions. By ramping the RF voltage, or by applying supplementary voltages on the end cap electrodes, or by combination of both, <mark>it is possible to keep only one ion in the trap, fragment it by inducing vibrations, and observe the fragments as they are sequentially ejected from the trap</mark>.  

The high efficiency for ion-trap MS/MS results from the parent and product ions remaining in a single ion trap and not transported from one chamber to another, eliminating transport losses. The application of wideband excitation (activation) and normalized collision energy leads to highly reproducible mass spectra. Hence, the main advantage of using a 3D QIT for GC-MS/MS is that full product ion spectra can be generated from trace amounts of pesticides for comparison with MS/MS libraries.  

The primary advantage of 3D QIT is that multiple MS/MS experiments can be performed quickly without having multiple analyzers. Hence, the introduction of MS/MS on a 3D QIT was a major breakthrough as it brought down the cost of tandem mass spectrometry. Unlike MRM using a triple quadrupole, however, MS/MS using 3D QIT is restricted to concurrent acquisition of a limited number of precursor ions. 


## References
<a href="#ref">[1] p69, Analysis of Pesticides in Food and Environmental Samples, CRC Press, 2008, edited by Jos&eacute; L. Tadeo</a>  
<a href="#ref">[2] p70, Analysis of Pesticides in Food and Environmental Samples, CRC Press, 2008, edited by Jos&eacute; L. Tadeo</a>  
<a href="#ref">[3] p71-72, Analysis of Pesticides in Food and Environmental Samples, CRC Press, 2008, edited by Jos&eacute; L. Tadeo</a>  

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
