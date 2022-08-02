---
authors: edited by Lenny Lin
categories:
date: "2022-06-28"
description:
draft: false
lastmod: "2022-07-01"
series: 
tags: []
title: Time-of-Flight Analyzer
toc: true
---

series: [Analysis of Pesticides in Food and Environmental Samples, edited by Jose L. Tadeo]
## Summary
) operates at unit mass resolution but with very fast scan rates.  
) has limited linear dynamic range.  
) Flight times are proportional to the square root of the `m/z value` of an ion.  

1) measures ions flight time based on the fact that ion velocity is mass-dependent.  The more energetic the ion, the deeper it penetrates the retarding field of the reflection before getting reflected. This allows an energetic ion, traveling a longer flight path, to arrive at the detector at the same time as the less energetic ions of the same mass.  
2) detects at trace levels while retaining full spectral information.  

<!--more-->

The use of TOF technology provides an innovative approach to overcoming the drawbacks that limit the exploitation of mass spectrometers for detecting pesticides at trace levels while retaining full spectral information as a tool for confirmation of identity. The design of the orthogonal acceleration (oa) TOF, into which pulses of ions are extracted orthogonally from a continuous ion beam, the availability of fast-recording electronics, together with improvements in signal deconvolution techniques, were major breakthroughs in the development of modern GC-TOF instruments.  

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-27 133857.png" style ="float: left" HSPACE="10" VSPACE="10"/>
As the name implies, separation of ions in a TOF mass analyzer is accomplished by measuring their flight time in a field-free tube <mark>based on the fact that ion velocity is mass-dependent</mark>. The ions generated in an EI source are initially accelerated to get discrete packages with a constant kinetic energy, which are ejected into the mass analyzer using pulsed electric field gradient oriented orthogonally to the ion beam.  

Reflectrons (ion mirrors) are used to compensate for variations in initial energy distribution. Ions are reflected based on their forward kinetic energy. <mark>The more energetic the ion, the deeper it penetrates the retarding field of the reflection before getting reflected. This allows an energetic ion, traveling a longer flight path, to arrive at the detector at the same time as the less energetic ions of the same mass</mark>.   

Ions are detected using a multichannel plate detector (MCP) and detection of "ion events" converted from an analog signal to a digital record. <mark>Flight times, which are proportional to the square root of the m/z value of an ion</mark>, are in the order of microseconds. Consequently, TOF MS can operate at very high repetition rates and between 20 and 500 spectra per second can be stored. The effort to exploit these unique features has resulted in the development of two types of commercial spectrometers differing in their basic characteristics: **1)** instruments using unit-resolution instruments that feature a high acquisition speed and **2)** elevated resolution analyzers with only moderate acquisition speed. The application potential of these approaches is obviously complementary.  Both approaches are characterized by high sensitivity due to improved mass analyzer efficiency and continuous acquisition of full range mass spectra. Mass analyzer efficiency of the TOF-MS instruments is as high as 25% in full spectra acquisition (quadrupole 0.1%).   

Generation of complete mass spectra from residues of pesticides even at trace levels enables searching against library reference spectra for identification. The fast repetition rate ensures that no changes in the ratios of analyte ions across the peak occur during the acquisition of the mass spectrum and, consequently, no spectral skew, which is commonly observed by scanning instruments, is encountered. The generation of full range mass spectra also provides the ability to review archived data for new compounds outside the scope of the initial analysis. For example, in response to an EU Rapid Alert in late December 2006, those laboratories within the EU using GC-TOF MS were able to look back again at historical data and identify residues of isofenphos-methyl even though no routine government testing program in any EU member state had included tests for isofenphos-methyl at that time.  

High-speed TOFs, operating at <mark>unit mass resolution</mark> but with very fast scan rates (e.g., 500 spectra/s), can provide the data density necessary to accurately define narrow chromatographic peaks typical for fast and ultrafast GC and GCxGC. The high data acquisition rate and the absence of any spectral skew allow overlapping signals to be automatically deconvoluted based on their mass spectra.   

The GC-TOF instruments with elevated resolution (typically 5000–7000 FWHM) and good mass accuracy (e.g., 5 ppm RMS) have so far had a more limited application to the analysis of pesticide residues. The elevated resolution and good mass accuracy can be significantly used to reduce the contribution from isobaric interference by evaluating data with a narrow mass window (typically 50 mDa), which improves detectability of the analytes. Measurement of an accurate mass of a particular ion also provides additional information for confirmation of identity for target compound analysis and, more importantly, aids the assignment of unknown compounds based on calculation of their elemental composition.   

High mass accuracy is attainable by using a lock mass calibration procedure for which a reference compound is continuously supplied into the ion source during analysis. On the basis of a previously performed mass calibration over a given mass range and a defined exact mass of the reference ion (the lock mass), the values of all masses in the acquired spectra are automatic and continually corrected. Mass accuracy varies with ion intensity. Care is required when applying exact mass windows as if the window is set too narrow, peaks may be underestimated or missed altogether. It is possible to search for compounds of interest by measurement of exact mass and isotope pattern of fragment ions and compare with the accurate masses in the reference spectra. Using this approach, the identification of the analyte can be based not only on retention time and EI mass spectrum, but thanks to the exact mass measurement also on elemental composition. In addition, the measurement of exact mass may aid the identification of unknown compounds through the calculation of elemental composition. In practice, this is a very demanding task as EI spectra rarely exhibit a molecular ion so a good knowledge of `the fragmentation mechanism` is required. 

<mark>The main disadvantage of the TOF as an analyzer for quantitative GC-MS is the limited linear dynamic range</mark> compared with conventional MS instrumentation. The analog signal from the ion detector is converted to a digital record by a fast analogto- digital (ADC)-based continuous averager, also called an integrating transient recorder (ITR). With an ITR, the ion rates can be increased so that many ions of the same m/z value arrive at the ion detector simultaneously. The result is an analog voltage pulse whose amplitude is approximately proportional to the number of ions in the pulse. An ADC samples the output waveform of the ion detector and periodically converts the measured analog voltage to a digital representation, which is sequentially stored in a digital memory to form a single record. Although the linear dynamic range of the ITR is limited to two orders of magnitude, it has been expanded to approximately four orders of magnitude by application of continuing improvements in both hardware and software features. 

While GC-MS, using EI with SIM on a single quadrupole, still provides the widest scope for pesticide residue analysis, GC-MS/MS and GC-TOF MS offer two unique solutions. However, both are still used by a few laboratories. Although initial purchase cost remains higher than conventional benchtop instruments, which may currently prohibit use within routine laboratories, both approaches offer considerable benefits and so usage is likely to grow. 




[^1]: p70, p73, Analysis of Pesticides in Food and Environmental Samples, CRC Press, 2008, edited by Jos&eacute; L. Tadeo