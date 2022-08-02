---
authors: edited by Lenny Lin
categories: Category
date: "2022-01-12"
description: Troubleshooting Pressure Issue
draft: false
lastmod: "2022-01-12"
series: 
tags: []
title: Chapter 02 LC Pressure Issue
toc: true
---

<figcaption><b>Figure </b>: </figcaption>
<img src = "/docs/images/"/>


System pressure is affected by a number of variables including:
1) the viscosity of the solvent used,   
2) column variables,  
3) flow rate and temperature.  

It is important to have <font style = "color:blue">a reference point</font> when comparing high or low pressures to the norm. This reference point should be the pressure generated in the system when everything is functioning correctly. It is a good idea to note the system pressure under normal operating conditions each day or each time your HPLC is used. This will allow you to spot any pressure trends that otherwise might go unnoticed.  

Pressure problems fall into one of three categories: high, low or fluctuating pressure. They can occur suddenly or be a gradual process. Sudden pressure rises tend to be due to particles from the sample, blocked or damaged tubing or column packed bed collapse. Gradual pressure rises can also be due to particles in the sample, but they can also arise from particles generated in the instrument, for example, debris from vial septa or degrading seals.  

Before releasing any high pressure build-up in a system, be aware that the solvent may form an aerosol or spray when loosening connections. Eye protection should be worn and ideally the connection to be loosened should be positioned above an adsorbent material to soak up all released solvents.   

The simplest way to troubleshoot pressure problems is using a systematic approach, as highlighted in the following tables for high, low and fluctuating pressure.  

[source](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)

<!--more-->

## High Pressure

### Thermo Guide
The most common causes of high pressure are <font color ="blue">blocked tubing</font> around <font color ="blue">the injector and column inlet</font>.   


<figcaption><b>Table: High pressure problem</b></figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 085339.png"/>

[source](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)


### Galak Guide


<table style="width:100%;">
<caption style="text-align:left", align = "top"><b>Problem: High Pressure</b></caption>
<colgroup><col style="width: 50%" /><col style="width: 50%" />
</colgroup>
<thead>
  <tr VALIGN=TOP class="header">
    <th><p>Problem</p></th>
    <th><p>solution</p></th>
  </tr>
</thead>
<tbody VALIGN=TOP>
  <tr class="odd">
    <td><p>1. The flow rate is set too high.
    </p></td>
    <td><p>Adjust the flow rate to an appropriate value.
    </p></td>
  </tr>
  <tr class="even">
    <td><p>2. Improper use of mobile phase or crystallization precipitation of buffer salt.
    </p></td>
    <td><p> The mobile phase was replaced and the column was rinsed.
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>3. The screen plate in front of the column is blocked.
    </p></td>
    <td><p>If permitted, flush the column, replace the sieve plate, and replace the column.
    </p></td>
  </tr>
  <tr class="even">
    <td><p>4. Protective column is blocked.
    </p></td>
    <td><p> Clean or replace the protective column.  
    </p></td>
  </tr>

</tbody>
</table>


### Sigma-Aldrich Guide

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Pressure Higher Than Usual</b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr VALIGN=TOP class="odd">
      <td><p>
      <img src = "/docs/images/Screenshot 2022-01-28 074045.png"/>
      </p></td>
      <td><p>
        1. Problem in pump, injector, in-line filter, or tubing.<br />
        <br />
        2. Obstructed guard column or analytical column.
      </p></td>
      <td><p>
        1. Remove guard column and analytical column from system. Replace with unions and 0.010'' I.D. or larger tubing to reconnect injector to detector. Run pump at 2-5 mL/min. If pressure is minimal, see Cause 2. If not, isolate cause by systematically eliminating system components, starting with detector, then in-line filter, and working back to pump. Replace filter in pump if present.<br />
        <br />
        2. Remove guard column (if present) and check pressure. Replace guard column if necessary. If analytical column is obstructed, reverse and flush the column, while disconnected from the detector. If problem persists, column may be clogged with strongly retained contaminants. Use appropriate restoration procedure (Table 2). If problem still persists, change inlet frit or replace column.
      </p></td>
    </tr>
  </tbody>
</table>


## Fluctuating Pressure

### Thermo Guide
The most common cause of fluctuating pressure is poorly primed lines with badly degassed solvents.  


<figcaption><b>Table: Fluctuating pressure problem</b></figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 091002.png"/>


### Galak Guide

1. There is gas in the pipeline, and the mobile phase degassing is not sufficient.  
The mobile phase continues degassing or changes the degassing method (e.g. online degassing).  

2. The one-way valve and the pump are damaged.  
Replace check the one-way valve and pump.  

3. Pressure fluctuation caused by mobile phase viscosity change.  
The solvent gradient elution was used.  

[source](https://galaklc.com/common-problems-for-hplc-system/)


## Continued Low Pressure

### Galak Guide
1. The flow rate is set too low.  
Turn the flow rate up appropriately.  

2. System leakage.  
Check column interface, pump, etc., to determine the location of leakage and repair.  

3. Improper column selection.  
Replace the appropriate column.  


### Sigma-Aldrich Guide

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: No Pressure/Pressure Lower Than Usual</b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr VALIGN=TOP class="odd">
      <td><p>
      <img src = "/docs/images/Screenshot 2022-01-27 224134.png"/>
      </p></td>
      <td><p>
        1. Leak.<br />
        <br />
        2. Mobile phase flow interrupted/obstructed.<br />
        <br />
        3. Air trapped in pump head. (Revealed by pressure fluctuations.)<br />
        <br />
        4. Leak at column inlet end fitting.<br />
        <br />
        5. Air trapped elsewhere in system.<br />
        <br />
        6. Worn pump seal causing leaks around pump head.<br />
        <br />
        7. Faulty check valve.<br />
        <br />
        8. Faulty pump seals.
      </p></td>
      <td><p>
        1. Check system for loose fittings. Check pump for leaks, salt buildup, unusual noises. Change pump seals if necessary. <br />
        <br />
        2. Check mobile phase level in reservoir(s). Check flow throughout system. Examine sample loop for obstruction or air lock. Make sure mobile phase components are miscible and mobile phase is properly degassed.<br />
        <br />
        3. Disconnect tubing at guard column (if present) or analytical column inlet. Check for flow. Purge pump at high flow rate (e.g., 10 mL/min.), prime system if necessary. (Prime each pump head separately.) If system has check valve, loosen valve to allow air to escape.<br />
        <br />
        4. Reconnect column and pump solvent at double the flow rate. If pressure is still low, check for leaks at inlet fitting or column end fitting.<br />
        <br />
        5. Disconnect guard and analytical column and purge system. Reconnect column(s). If problem persists, flush system with 100% methanol or isopropanol.<br />
        <br />
        6. Replace seal. If problem persists, replace piston and seal.<br />
        <br />
        7. Rebuild or replace valve.<br />
        <br />
        8. Replace seals.
      </p></td>
    </tr>
  </tbody>
</table>


## Check List for Troubleshooting

<input type="checkbox">
  <label> Flow rate</label><br>
<input type="checkbox">
  <label> Pressure transducer</label><br>
<input type="checkbox">
  <label> Detector</label><br>

  