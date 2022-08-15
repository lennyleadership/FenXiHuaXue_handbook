---
weight: 1
title: Troubleshooting strategy
authors: Lenny Lin
categories:
tags: [Troubleshooting Strategy]
date: "2022-07-07"
description: null
draft: false
lastmod: "2022-07-18"
series:
toc: true
---
> *A problem well stated is a problem half solved*.  
> &ensp;- Charles Franklin Kettering

<!--more-->

---
The first step is to list the potential root causes to the problem.  Build a fishbone diagram if you wish. If you had a problem of sensitivity with LC-MS/MS.  The root causes would be:
1) MS part
1) ESI  
2) dirty ion source
3) 



## Part I Building up a system

### At the beginning
The program starts at the very beginning when the instrument was commissioned.  Collect the following information at its best condition.
&emsp;) The instrument performance at its best condition.  The best condition would be the time when the instrument was commissioned or the PM was conducted.  Such performance includes, but not limited to, key parameters on the tuning report, such as electron multiplier voltage(EMV) of detector.  Plot the parameters.   
&emsp;) The instrument response to pure standard at the LOQ level when validating the method.  We would run ten replicates of pure standard every day for three days.  Collect the following parameters, but not limited to, `analyte to internal standard ratio`, `qualifier to quantifier ratio`. Plot the parameters, establish action limit.   
[Note: some people call this practice as `system suitability test`.]
&emsp;) Setup binders of troubleshooting cases.  
&emsp;) Document (screen shot, print) acceptable peak shape for analyte(s) most sensitive to column degradation.  
&emsp;) Build up a database of problems and associated troubleshooting so that solutions can be searchable when needed.

**Notes:**  
&emsp;1. Prepare standard solutions in injection matrix in bulk, aliquot to autosampler vials and store ready for use at -20<sup>0</sup>C (or best temperature for stability).


### During the routine analysis
On top of the scheduled preventive maintenance, the program is executed on a regular basics to monitor the health condition of instrument.
&emsp;) run pure standard at the LOQ level, double blank, and method blank before run. Plot monitored parameters, and check the trend.
&emsp;) Plot pressure traces.

**Table 3 System Suitability Test Outline**  
**Routine Actions:**  
&emsp;1. 3-5 injections of pure standard(s) and blank in injection matrix (and internal standards if desired)  
 
&emsp;3. Compare means & %CVs to action limits  
<br>
  
 
<br>
**Options**  
&emsp;1. Verify acceptable separation of peaks most sensitive to column degradation (if applicable).  
&emsp;2. 


## Part II Troubleshooting

### Level I: Easily-fixed problem
rule out operator false, such as wrong injection,  
They are:
) Operator failures;
) 

### Level II: complex problem
) investigation.  
&emsp;) go over the monitoring charts, and compare the previous trend.
&emsp;) discuss with the analyst.  
) break the system down to LC and MS.














Troubleshooting workflow:
) rule out simple problem.  
) isolate area. [sample preparation, mass spectrometer, HPLC,  
) 
) 

Questions to be answered:  
1) Did electrospray ionization work properly?
2) Did mass spectrometer work properly? [autotune reports, such as declustering potential, collision energy, collision exit cell potential, pressure]
3) Did LC work properly? [mobile phase ageing



Steps:  
1) check mass spectrometer performance. (autotune reports, parameters, asymmetric spray (blockage))
2) 



Useful diagnostic tools: 
1) a known standard  
2) unscheduled method  
3) monitoring plots of internal standards, blank, instrument parameters  
4) infusion the tuning solution to check mass spectrometer  
5) check autotuning reports.  
6) 


---
sensitivity change

make new mobile phase A with pH modifier(aqeuous solution)  rational: the pH promote the charged state of the analyte over its neutral species.
mobile phase was contaminated attributing to rising baselines, noise or spikes.

chromatography: 