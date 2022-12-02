---
authors: Lenny Lin
categories: null
date: "2022-03-17"
description: 
draft: false
lastmod: "2022-06-28"
series: null
tags: null
title: Matrix Effects
toc: true
---

Ways of eliminating, reducing or compensating matrix effects:  
Reduce the injection volume.  
Dilute sample or extract.  
<br>
More extensive sample clean-up and better extraction  
Use mixed-mode SPE.  
Extra wash steps in SPE.  
<br>
Optimize mobile phase (including organic modifier, additives, buffers, pH)  
Eluotropic strength or elution profile [not understand].  
<br>
Change the column chemistry,  
use longer column,   
use Ultra Fast LC (UFLC) or smaller particles to improve resolution.  
<br>
Switch from ESI to APCI.  
Switch from positive ionization mode to negative ionization mode.  
<br>
External matrix-matched calibrators (i.e. standards with the same or similar matrix composition as the analysed sample) can be used to compensate for matrix effects.    
<br>
Internal standards (IS) can be used to compensate for variations in injection, sample preparation, instrumental parameters and also matrix effects.  

Other less often used calibration techniques are echo peak technique, standard addition, extrapolative dilution and (segmented) post-column standard addition. 



<!--more-->

## Definition

Matrix effects are defined as any change in the ionization process of an analyte due to a co-eluting compound; this can result in ion suppression or ion enhancement.  

The co-eluting compounds responsible for this phenomenon can also be other substances than matrix components.  

Matrix effects are mostly observed in the beginning of a chromatographic run, since all polar and non-retained substances elute close to the solvent front.  

Until today the exact mechanism is still unknown.  

Matrix effects are compound-dependent: a study showed that more polar analytes are more sensitive to loss of signal.  

Matrix effects depend on the matrix: as the complexity of the samples increases, more and more matrix effects can be seen. Considering the different working mechanism of the two most popular ionization interfaces, the mechanism of matrix effects will also be different for ESI and APCI. Several hypotheses on the mechanism of ion suppression have been formulated and will be briefly discussed here. For ESI, four mechanisms have been proposed: two mechanisms focus on the effect of interfering compounds on the ionization of the analyte (mechanism 1 and 4), the other two on the droplet formation and evaporation resulting in gas phase ions. Mechanisms 1, 2 and 3 occur in liquid phase, mechanism 4 takes place in gas phase.  

1) As described in section 4.2, at high concentrations, ionization saturation occurs. In samples containing interfering compounds, the limit concentration can be easily reached. At that point, the analyte of interest and other substances will have to compete for ionization. Ion suppression is caused by a limited number of charges on the droplet surface or more likely by analytes that are trapped in the centre of the droplet and will not be able to access the surface for gas emission (15). 2) Non-volatile compounds may precipitate with the analyte resulting in solid formation (27). According to the ion evaporation model, precipitates may also prevent the droplets to reach the critical radius and electrical surface field necessary for ion emission and thus limit the transfer of analytes to the gas phase (28). 3) Interferences can change the viscosity and the surface tension of the droplets, thereby reducing solvent evaporation and the ability of the analyte to reach the gas phase (29). 4) Droplets can be contaminated with substances which may evaporate as neutrals. If the gas phase proton affinity of these neutrals is higher than that of the analyte, transfer of a proton from the analyte to the interference may occur in the gas phase (20). APCI suffers less from matrix effects than ESI, since there is no competition between the analytes to enter the gas phase in ionized form (30). 1) Solid formation may be a mechanism of ion suppression in APCI (27). 2) Gas phase reactions such as described in ESI mechanism 4 may cause matrix effects (30). 3) The efficiency of charge transfer from the corona needle to the analyte may be changed by the presence of interferences (30). Although most research has been focusing on ion suppression, ion enhancement may also occur (26,31). Gas phase reactions for both ESI and APCI and changed charge transfer from the corona needle for APCI seem to be possible explanations for this phenomenon. Whether the result is ion suppression or ion enhancement, the co-elution of an analyte with interfering compounds can seriously affect precision, accuracy and sensitivity of a method. Therefore testing for matrix effects should be an integral part of LC-MS method validation, especially in forensic toxicology using often dirty samples. If possible, strategies to decrease matrix effects should be applied.


## Solution

Changes in five domains can eliminate, reduce or at least compensate for matrix effects and will be discussed here: the amount of sample, sample preparation, chromatography, mass spectrometry and calibration.  


### Amount of sample

Reducing the injection volume is a simple way to reduce the number of species competing for ionization. However, sensitivity is reduced. The sample or the extract can be diluted, again the main drawback being the decrease of limits of detection.


### Sample Preparation

<mark class = "lemon">More extensive sample clean-up and better extraction methods</mark> results in fewer co-eluting components and thus less matrix effects. In all papers comparing sample preparation, sample dilution and/or protein precipitation showed the greatest amount of matrix effects, while SPE and LLE resulted in cleaner extracts. Especially mixed-mode SPE, i.e. SPE that combines two retention mechanisms, was very useful to avoid matrix effects. When using SPE, the protocol should be carefully evaluated, since not only the analytes of interest but also interfering substances can be concentrated, magnifying matrix effects. To optimize the SPE procedure, extra wash steps can be added or the elution solvent can be optimized.


### Chromatography

Changing chromatography to reduce the degree of co-elution between interfering compounds and the analyte of interest can help in reducing matrix effects. Therefore, the mobile phase can be optimized: changing organic modifier, mobile phase additives, buffers, pH, eluotropic strength or elution profile may reduce matrix effects. Changing column parameters can also be effective for reducing matrix effects: for example changing column chemistry changes selectivity and using a longer column enhances separation. Moreover, when using columns with smaller particles or UFLC, resolution is improved, thus reducing matrix effects. Other researchers used LC/LC, i.e. the coupling of two columns with different retention mechanisms in order to achieve better separation. Generally, the higher the flow rate, the higher the level of matrix effects since more organic material requires ionization at the same time. Flow rate can be drastically reduced by using a nanosplitting device or a post-column split.  


### Mass Spectrometry

In general, matrix effects are more pronounced in ESI than in APCI, so changing to APCI might help. The negative ionization mode is considered more selective than the positive mode since fewer compounds give a signal in the negative mode. Switching to negative mode may lower matrix effects. Of course, in this case, the analyte should be detectable in both ionization polarities.  

### References:

LC-MS/MS in forensix toxicology: What about matrix effects? Jan, 2011, Ruth Verplaetse
