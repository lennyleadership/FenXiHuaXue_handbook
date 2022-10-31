---
weight: 3
title: Maximize Sensitivity
authors: null
categories: null
tags: null
description:  
draft: false
date: "2022-10-31"
lastmod: "2022-10-31"
series: null
toc: true
---



<!--more-->
---

## Introduction

The prerequisite of any highly sensitive analysis via HPLC-MS (high performance liquid chromatography coupled to mass spectrometry) is the use of ultrapure solvents and reagents and careful handling of all associated materials, consumables, and systems. This prevents any contamination throughout the entire sample handling process from preparation to MS detection, and improves sensitivity.

In the following sections, various measures and options for maximized LC-MS sensitivity and low limit of detection (LOD) are shown. Each and every tip avoids contaminations causing signal suppression, adduct formation, elevated background noise and increased spectrum complexity.

## Solvents & Additives - General

Typical solvents utilized in LC-MS include water, acetonitrile, methanol, isopropanol, and *n*-propanol. Additives such as acids (e.g., formic acid), bases (e.g., ammonia) or buffers (e.g., ammonium acetate) are used to enable the protonation or deprotonation of the analytes.

The quality of the above-mentioned solvents and additives strongly influences the sensitivity of MS detection; therefore, utilization of MS grade solvents and ultrapure additives is mandatory. Make sure that these reagents are labeled as LC-MS grade by the manufacturer.

Generally, organic solvents for HPLC, such as acetonitrile and methanol, are available in three qualities: Isocratic grade, gradient grade and hypergrade for LC-MS LiChrosolv ^&reg;^. For MS analysis, hypergrade quality solvents should be used to ensure best performance and reliable results.

With regard to water, bottled or Milli-Q ^&reg;^ ultrapure water from water purification systems are suitable for use with MS instrumentation. In case of low water consumption, bottled water is preferable, whereas Milli-Q ^&reg;^ water is suggested in an environment with higher consumption. Milli-Q ^&reg;^ systems deliver type I water and are a perfect match with LC-MS analysis. They should be used/flushed regularly in order to maintain or even further improve water quality.

Buffers are utilized to set and control the pH of a specific chromatographic separation and to protonate or deprotonate analytes in solution, which can support the electrospray ionization process. For LC-MS, only volatile buffers and additives such as ammonium formate or acetate or triethylamine should be utilized. The use of nonvolatile buffers (e.g., sulfates, phosphates, borates) will cause precipitation in the MS source and ultimately result in tedious cleaning procedures. High buffer concentrations might lead to signal suppression.

Buffers ionize an analyte molecule M, but the formation of adducts [M+buffer] with, e.g., ammonium, formate or acetate is possible. This causes additional signals with specific *m/z* values in a spectrum which may compromise quantitative analyses. Consequently, for samples with high salt load such as food, body fluids or tissue, a desalting step using solid phase extraction (SPE) (e.g., Supel™-Select HLB, or LiChrolut ^&reg;^ and Supelclean ^&reg;^ cartridges) is recommended.

Buffers should be prepared by titration of the respective acid and base, as their purity is normally higher than the related salts. If the use of salts is necessary, an MS analysis of those used should be performed prior to use application to determine if and what type of contaminant is present in the salts.

Impurities in or contaminants of solvents and additives can accumulate on the stationary phase and elute as ghost peaks in gradient runs (**Figure 1**). This scenario may occur when the column is equilibrated under highly aqueous conditions prior to a gradient run. Ghost peaks can even appear without equilibration if the concentration and/or retentivity of contaminants is high and/or the starting conditions of a gradient are highly aqueous. To avoid ghost peaks in gradient runs, column equilibration time should be kept as short as possible and the flushing volume should not exceed ten column volumes.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5cebc8ae-720c-4b9d-86c2-1252dd47e24f/accumulation-of-contaminants.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5cebc8ae-720c-4b9d-86c2-1252dd47e24f/accumulation-of-contaminants.png)

Figure 1.Accumulation of contaminants on an HPLC column

Figure 1.Accumulation of contaminants on an HPLC column during equilibration and elution via a gradient profile; peaks attributed to plasticizers are marked with an asterisk (*).

| Conditions: |  |
| --- | --- |
| Instrument: | Bruker Esquire 6000plus |
| Mobile phase: | A: water/acetonitrile 95/5 (v/v) + 0.1% formic acid |
|  | B: acetonitrile + 0.1% formic acid |
| Gradient: | 0 min 100% A, 3 min 5% A, 5 min 5% A |
| Flow rate | 0.4 mL/min |
| Temperature: | 25°C |
| Detector: | pos. ESI-MS (TICs) |
| Sample: | plasticizers added by the immersion of plastic tubing in aqueous solvent A |

Strong acids such as hydrochloric acid, sulfuric acid, or nitric acid should be avoided because they tend to form strong ion pairs with analytes and, therefore, make the analyte unsuitable for any type of ionization. Additionally, some of these strong acids have unfavorable oxidizing properties.

Many laboratories use trifluoroacetic acid (TFA) in order to form ion pairs with peptides and proteins and to improve subsequent HPLC separation; however, TFA causes strong ion suppression of the analyte during MS detection and may as well contaminate the mass spectrometer. If the use of TFA is necessary, then a weak acid or isopropanol should be added to help decrease the signal suppression effect. Alternatively, difluoroacetic acid (DFA) is an option that decreases the signal suppression effect (as compared to using TFA).

## Solvents & Additives – Storage & Handling

Solvents should be stored in the original manufacturer’s bottle; this can be either surface treated amber or borosilicate glass. Adjustment of the bottle size to specific needs is recommended, because decanting/ transferring to a different container, a source of contamination, should be avoided whenever possible.

Avoid standard clear or soda-lime glass bottles. Leaching alkalines and silica can form adducts with analytes.

Bottles have to be sealed and connected to the HPLC system using professional caps, adapters, and tubing directly mounted to the solvent bottle. Any homemade solution will likely cause contamination of the solvent or eluent and could lead to the evaporation of organic solvents into the lab atmosphere.

Avoid plastic devices such as bottles, funnels, beakers, or gloves which can leach additives like plasticizers, anti-static agents, stabilizers or anti-slipping agents (**Figure 2**). The only exceptions are devices that have been tested for leachables and extractables by the manufacturer, e.g., pipette tips or syringes.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/adc8f174-e4f0-4fd1-a104-22d618a2691f/mass-spectra-of-two-milli-q.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/adc8f174-e4f0-4fd1-a104-22d618a2691f/mass-spectra-of-two-milli-q.png)

Figure 2.Mass spectra of two Milli-Q ^&reg;^ water samples stored in polypropylene (A) and clean amber glass bottles (B), respectively (bottom), and TICs of the same samples (top). The analyses were performed via direct injection of the solvents into the MS operated in positive ESI mode.

## Laboratory Equipment

Cleaning of laboratory equipment and vessels can most simply be done by evaporation in a fume hood, as all reagents used in MS applications are volatile and of high purity. In cases where contamination is observed, flushing with MS grade solvents will be necessary in order to properly clean the equipment.

If a dishwasher needs to be used for any reason, it is critical that after washing, the vessels are flushed/ rinsed with an MS grade solvent multiple times.

## HPLC Column

The choice of an HPLC column dimension is guided not only by factors such as sample size, detection technique, and necessary loadability, but also by economic considerations such as reducing solvent consumption. A decrease in column internal diameter (i.d.), while geometrically scaling injection volume and flow rate accordingly, is a simple means of also improving sensitivity of a given separation.

A possible and frequent but often overlooked source of contamination in an LC-MS run is the chromatographic column itself. Many of the silica-based bonded phases are inherently prone towards bond/phase cleavage by hydrolysis, mainly at acidic pH (e.g., below pH 2), a phenomenon referred to as column bleeding (**Figure 3**).

The use of a washing protocol can help to decrease the negative effect of column bleed. Alternatively, a column should undergo up to ten gradient runs from strongly aqueous to strongly organic before use with MS.

## HPLC System

A proper setup of the HPLC system itself can contribute to increased sensitivity as well. An important parameter is the minimization of dead volume, i.e., the volume of all system parts from the injector to the detector cell, except for the HPLC column volume. Large dead volumes can cause peak broadening, tailing, or splitting and lead to poor resolution and decreased performance, and hence can decrease sensitivity and prevent detection of low abundant analytes. Consequently, all system parts (tubing, connectors, fittings) must contribute the smallest possible dead volumes.

Replace the pump inlet filter every 1 to 2 months or after changing from acetonitrile to methanol (or vice versa) as a solvent. This maintenance will lower the baseline noise and protect the system and column from pump debris.

Eluent filter frits (from solvent inlet filters) should be made out of stainless steel or PEEK rather than glass.

Cleaning of the latter is tedious, as buffer residue is hard to remove, and silica and alkali might be leached out of the glass filter and form adducts.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/664922d0-7199-4115-b115-4291efd51aa0/quantification-of-hilic-column.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/664922d0-7199-4115-b115-4291efd51aa0/quantification-of-hilic-column.jpg)

Figure 3.Quantification of HILIC column bleeding of various columns

Figure 3.Quantification of HILIC column bleeding of various columns in comparison with alternative products measured by mass spectrometry.

| Conditions: |  |
| --- | --- |
| Column: | As indicated |
| Mobile phase: | acetonitrile/25 mM ammonium acetate pH 6.8 80/20 (v/v), 6 min. |
| Flow: | 0.8 mL/min |
| Temperature: | 50 °C |
| Detector: | Ion-trap MS (m/z 50-2000) |

## General Recommendations

The specific requirements of different chromatographic problems might make the use of various mobile phase compositions necessary, ranging from aqueous to organic. As a general recommendation, the water content in an eluent used in LC-MS should be set to 5 to 80% in order to work trouble-free and with a stable spray.

If the water content is below 5%, buffers may precipitate in the eluent and the HPLC system. A countermeasure can be the use of a suitable organic solvent or a decrease of buffer concentration in the eluent. Buffer solubility in utilized solvents (and gradient range) should always be checked prior to analysis.

A water content of more than 80% might lead to a breakdown of the MS spray. Several options help to keep the MS spray working.

1. Decrease in the surface tension of the eluent by addition of a volatile organic solvent such as acetonitrile or methanol to the mobile phase after the LC system and in front of the MS source.
2. Reduction of the flow delivered to the MS by means of a split or column exchange.
3. Manipulation of the MS source conditions (increase in dry gas temperature or flow).

In order to avoid microbial contamination of both system and mobile phase, and phase collapse, water content of the mobile phase should not be set above 95%. If a highly aqueous mobile phase is necessary, 0.05% sodium azide can be added to the eluent.

Alternatively, regular flushing of the HPLC system with organic solvent, preferably isopropanol or methanol, prior to standby is mandatory. Do not use acetonitrile, because acetonitrile can polymerize and block system valves.

## Conclusion

Mass spectrometry is a powerful technique for identification and quantification of molecules within complex mixtures. The success of mass spectrometry strongly depends on reducing contamination throughout the entire LC-MS workflow: from sample preparation to equipment cleaning. An important first step in this process is the exclusive use of highest quality materials for LC-MS, including solvents, buffers, reagents and columns. The combination of ultra-pure solvents and reagents with contamination-free handling ensures maximized LC-MS sensitivity and low LODs.

*First published in Chromatography Today*, volume 10, issue 4, *Buyers Guide* November/December 2017.