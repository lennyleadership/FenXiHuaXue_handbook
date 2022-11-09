---
weight: 1
title: LC Baseline Irregularities
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: Baseline Irregularities
draft: false
lastmod: "2022-07-16"
series: 
tags: [Sensitivity]

toc: true
---

<!--more-->

## Thermo Guide

Baseline irregularities can be non-cyclic (erratic) or cyclic (follow a pattern). They can originate from:

1) electrical interferences,   
2) detector faults,  
3) solvent impurities,   
4) column contamination etc.   

To isolate the source of a baseline irregularity, it is important to determine whether the problem lies with the fluid path, detector or electrical connections. This can be achieved by following the simple steps below:  

1. Turn off the instrument pump – fluid flow must be zero  

2. Monitor the baseline for 5 to 10 minutes. Note if there is any improvement in the baseline’s appearance. If yes, then the problem lies within the instrument fluid path. If no, the problem is either electrical or detector related.  

3. Disconnect the detector electrical cables from the A/D interface with the PC, integrator and chart recorder, i.e. the data handling devices. Attach a jump source to the input terminals on the data- handling device (a crocodile clip, paper clip etc). If the noise ceases, then the problem is within the detector or it’s electrical connections. If the noise continues, then the problem is within the data-handling device.  

Data-handling device troubleshooting is beyond the scope of this guide.We recommend that you contact your instrument provider for this service.  

The sections provide a quick reference guide for typical baseline irregularities, their causes and corrective action that can be taken to cure the problem.  


### Non-Cyclic Noise – Fluid Path Problems

The most common cause of non-cyclic baseline noise related problems is air in the system. To overcome this, all solvents should be thoroughly degassed prior to use, all lines should be purged with solvent and the pump should be thoroughly primed.  

Air bubbles can obscure the detector flow cell and cause baseline noise – be aware that from time to time, the cell may require cleaning and/or removal of air bubbles.  

<figcaption><b>Figure </b>: Non-Cyclic Noise – Fluid Path Problems</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 100231.png"/>


<figcaption><b>Figure </b>: Non-Cyclic Noise – Fluid Path Problems</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 101931.png"/>


### Non-Cyclic Noise – Detector Electronics Problems

Note: This section is based on HPLC with DAD detector.  

The most common cause of problems related to electronic baseline noise is the detector. Usually, if the detector is allowed insufficient time to equilibrate before an injection is performed, then the resultant chromatogram will contain spurious peaks and there will also be some evidence of baseline drift.  

If the problem occurs after routine maintenance, check that all the cables are securely seated in their sockets and that the correct cable is in the correct socket. Also check that all settings have been returned to their positions prior to the routine maintenance.  


<figcaption><b>Figure </b>: Non-Cyclic Noise – Detector Electronics Problems</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 100424.png"/>


<figcaption><b>Figure </b>: Non-Cyclic Noise – Detector Electronics Problems</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 110949.png"/>


### Cyclic Noise – Detector Related Problems and Others

The most common cause of cyclic baseline noise is the detector. Usually, if the detector is allowed insufficient time to equilibrate before an injection is performed, then the resultant chromatogram will contain spurious peaks and there will also be some evidence of baseline drift.  

<figcaption><b>Figure </b>: Cyclic Noise – Detector Related Problems and Others</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 111505.png"/>


<figcaption><b>Figure </b>: Cyclic Noise – Detector Related Problems and Others</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 111839.png"/>


## Sigma-Aldrich Guide

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Baseline Drift </b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 110401.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1. Column temperature fluctuation. (Even small changes cause cyclic baseline rise and fall. Most often affects refractive index and conductivity detectors, UV detectors at high sensitivity or in indirect photometric mode.)<br />
        <br />
      2. Nonhomogeneous mobile phase. (Drift usually to higher absorbance, rather than cyclic pattern from temperature fluctuation.)<br />
        <br />
      3. Contaminant or air buildup in detector cell.<br />
        <br />
      4. Plugged outlet line after detector. (High pressure cracks cell window, producing noisy baseline.)<br />
        <br />
      5. Mobile phase mixing problem or change in flow rate.<br />
        <br />
      6. Slow column equilibration, especially when changing mobile phase.<br />
        <br />
      7. Mobile phase contaminated, deteriorated, or not prepared from high quality chemicals.<br />
        <br />
      8. Strongly retained materials in sample (high k’) can elute as very broad peaks and appear to be a rising baseline. (Gradient analyses can aggravate problem.)<br />
        <br />
      9. Detector (UV) not set at absorbance maximum but at slope of curve.
      </p></td>
      <td VALIGN=TOP><p>
      1. Control column and mobile phase temperature, use heat exchanger before detector.<br />
        <br />
      2. Use HPLC grade solvents, high purity salts, and additives. Degas mobile phase before use, sparge with helium during use.<br />
        <br />
      3. Flush cell with methanol or other strong solvent. If necessary, clean cell with 1N HNO3 (never with HCl and never use nitric acid with PEEK tubing or fittings.)<br />
        <br />
      4. Unplug or replace line. Refer to detector manual to replace window.<br />
        <br />
      5. Correct composition/flow rate. To avoid problem, routinely monitor composition and flow rate.<br />
        <br />
      6. Flush column with intermediate strength solvent, run 10-20 column volumes of new mobile phase through column before analysis.<br />
        <br />
      7. Check make-up of mobile phase.<br />
        <br />
      8. Use guard column. If necessary, flush column with strong solvent between injections or periodically during analysis.<br />
        <br />
      9. Change wavelength to UV absorbance maximum.
      </p></td>
    </tr>
  </tbody>
</table>


<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Baseline Noise (regular)</b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 111656.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1. Air in mobile phase, detector cell, or pump.<br />
        <br />
      2. Pump pulsations.<br />
        <br />
      3. Incomplete mobile phase mixing.<br />
        <br />
      4. Temperature effect (column at high temperature, detector unheated).<br />
        <br />
      5. Other electronic equipment on same line.<br />
        <br />
      6. Leak.
      </p></td>
      <td VALIGN=TOP><p>
      1. Degas mobile phase. Flush system to remove air from detector cell or pump.<br />
        <br />
      2. Incorporate pulse damper into system.<br />
        <br />
      3. Mix mobile phase by hand or use less viscous solvent.<br />
        <br />
      4. Reduce differential or add heat exchanger.<br />
        <br />
      5. Isolate LC, detector, recorder to determine if source of problem is external. Correct as necessary.<br />
        <br />
      6. Check system for loose fittings. Check pump for leaks, salt buildup, unusual noises. Change pump seals if necessary.
      </p></td>
    </tr>
  </tbody>
</table>


<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Baseline Noise (irregular)</b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 112003.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1. Leak.<br />
        <br />
      2. Mobile phase contaminated, deteriorated, or prepared from low quality materials.<br />
        <br />
      3. Detector/recorder electronics.<br />
        <br />
      4. Air trapped in system.<br />
        <br />
      5. Air bubbles in detector.<br />
        <br />
      6. Detector cell contaminated. (Even small amounts of contaminants can cause noise.)<br />
        <br />
      7. Weak detector lamp.<br />
        <br />
      8. Column leaking silica or packing material.
      </p></td>
      <td VALIGN=TOP><p>
      Check system for loose fittings. Check pump for leaks, salt buildup, unusual noises. Change pump seals if necessary.<br />
        <br />
Check make-up of mobile phase.<br />
        <br />
Isolate detector and recorder electronically. Refer to instruction manual to correct problem.<br />
        <br />
Flush system with strong solvent.<br />
        <br />
Purge detector. Install backpressure regulator after detector. Check the instrument manual, particularly for RI detectors (excessive backpressure can cause the flow cell to crack).<br />
        <br />
Clean cell.<br />
        <br />
Replace lamp.<br />
        <br />
Replace column and clean system.
      </p></td>
    </tr>
  </tbody>
</table>
***


