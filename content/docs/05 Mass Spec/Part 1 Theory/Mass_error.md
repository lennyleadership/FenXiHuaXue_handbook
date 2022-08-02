---
authors: edited by Lenny Lin
categories:
date: "2022-06-28"
description:
draft: false
lastmod: "2022-07-07"
series: 
tags: []
title:  Mass Error - Terminology
toc: true
---




<!--more-->

## Mass

**Nominal mass**: It is the mass of an ion or molecule calculated using <mark>the mass of the most abundant isotope of each element rounded to the nearest integer value</mark> and equivalent to the sum of the mass numbers of all constituent atoms.  

**Accurate mass**: It is <mark>The experimentally determined mass of an ion</mark> measured to an appropriate degree of accuracy and precision used to determine, or limit the possibilities for, the elemental formula of the ion. &nbsp;&nbsp;<sup>(</sup>[^1]<sup>)</sup>  

**Exact mass**: It is the calculated mass of an ion whose elemental formula, isotopic composition and charge state are known, i.e., it is the theoretical mass. The IUPAC definition constricts the definition to using one isotope of each atom involved, usually the lightest isotope, but generalizes the definition to cover an ion or neutral molecule &nbsp;&nbsp;<sup>(</sup>[^2]<sup>)</sup>. The charge state is relevant as the mass of the electron (0.00055 Da), or multiple charges, may not be negligible in the context of mass measurement. 

A mass spectrum can be annotated with its nominal masses or accurate masses, to an appropriate number of significant figures. The IUPAC unit of mass is the unified mass unit (u) &nbsp;&nbsp;<sup>(</sup>[^2]<sup>)</sup> and is also referred to as the Dalton (Da) although this is not an SI unit. The term atomic mass unit (amu) is a redundant unit although it is still in wide use.  

A mass spectrometer measures mass-to-charge, and m/z should normally be used when referring to the mass scale.

## Accuracy and Precision

**Accuracy**: The **proximity** of the experimental measurement to the true value (exact mass). When a measurement is close to the true value we say it is accurate and when it is not we say it is inaccurate.   
Normally, mass measurement error would be used to describe the accuracy of a single reading.   
**Precision**: The **repeatability** of the measurement reflecting random errors. Random errors cause measurements to fall on either side of the average experimental measurement and affect the precision of the set of measurements. When a set of mass measurements of one ion species lie close together we say the measurements are precise, and when not we say the measurements are imprecise.  
Two other items of terminology which must be clarified are:  
**Repeatability**: This is <mark>the short-term precision</mark> of multiple replicate experimental measurements made under similar conditions, i.e., the same instrument, operator and over a limited time, normally the same day. **Reproducibility**: It refers to differences among experimental measurements made under different circumstances i.e., a measurement of the same quantity made by different operators, even different instruments and often with a significant time difference between groups of measurements.  


## Estimation of Mass Measurement Statistics
The mass measurement error (or accuracy) of a single reading will be:  
$&Delta;m_i = (m_i - m_a)$ in Da   
<br>
$&nbsp;&nbsp;= (m_i - m_a) \times 10^3$ in mDa   
<br>  
$ &nbsp;&nbsp; = \frac{(m_i - m_a)}{m_a} \times 10^6$ in ppm  

The symbol m<sub>a</sub> has been used here to represent exact mass as the symbol m<sub>e</sub> represents the electron mass and the symbol m<sub>ex</sub> could be interpreted as experimental mass and not exact mass.  

The term “error” is defined as the difference between an <mark>individual</mark> measurement and the true value, where  $\Delta$m<sub>i</sub> can be positive or negative.  

It is important to remember that the term “error” should only be used in connection with the result of a <mark>single</mark> measurement and not used to represent an averaged measurement (see later discussion).  

Errors in relation to the exact mass measurement are only apparent when the compound’s composition is known.   

The term “<mark>mass deviation</mark>” has been proposed to the <mark>proteomics</mark> community for reporting a single mass measurement error. These authors define mass deviation as “the measured mass minus the calculated mass,” and recommend this instead of using “mass accuracy”. Whilst it is correct to point out that the term accuracy should not be used for a single measurement, there is no necessity to redefine this as deviation. In fact, IUPAC defines deviation as “the difference between an observed value and the arithmetic mean of the set to which it belongs.” This is not the same definition as that for the error of a measurement, which IUPAC defines as “the result of a measurement minus the true value.” Thus, the term mass deviation is not appropriate to describe a mass measurement error. They further define the term maximum mass deviation (MMD), “this is the cutoff value used in database search. Only peptide sequences with a calculated mass within this tolerance are reported as hits.” 
 
ppm error is a quantity frequently used to report mass errors and varies along the mass scale.

    
A simple way to indicate the accuracy of measurement is the use of the significant figure convention. For example, if experience and observation of mass measurements showed measurements to give ~0.001 Da accuracy, then the mass would be reported to one more significant figure. 


<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-07 121142.png"/>
<figcaption><b>Figure </b>: Illustration of the meaning of the terms accuracy, precision, average experimental mass and calculated exact mass of a dataset. (a) Histogram (plotted for convenience as a continuous probability curve) showing accuracy i.e., the difference between the calculated exact mass (reference quantity) and the measured average mass (experimental quantity). Precision is a measure of the spread of mass measurements of the dataset, and relate to the repeatability of the measurements undertaken. (b) Plot of nine repeat accurate mass measurements at mass 400 Da, in the range 399.990 to 400.010 Da, illustrating four types of statistical outcomes of data that is, (i) accurate and precise, (ii) accurate but imprecise, (iii) inaccurate but precise, and (iv) inaccurate and imprecise.</figcaption>

[^1]: Accurate Masses for Structure Confirmation, M.L. Gross, J. Am. Soc. Mass Spectrom., 5 (1994), p. 57   
[^2]: Murray, K. K.; Boyd, R. K.; Eberlin, M. N.; Langley, G. J.; Li, L.; Naito, Y. Standard Definitions of Terms Relating to Mass Spectrometry; International Union of Pure and Applied Chemistry (IUPAC), 2006; 3rd draft document. Online http://www.msterms.com/.