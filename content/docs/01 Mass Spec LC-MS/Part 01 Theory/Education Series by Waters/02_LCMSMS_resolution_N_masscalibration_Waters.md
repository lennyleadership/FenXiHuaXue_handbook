---
authors: Scott Freeto, edited by Lenny Lin
categories: null
date: ""
description: 
draft: false
lastmod: "2022-06-20"
series: null
tags: null
title: Quadupole Resolution & Mass Calibration
toc: true
---
LC-MS/MS Education Series 2/3 by Waters  

<iframe width="360" height="200" src="https://www.youtube.com/embed/vkT0nrbeoDY" title="LC-MS/MS Education Series: Quadrupole Resolution and Mass Calibration" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<!--more-->

Hi, I'm Scott Freeto and I'm a mass spec application specialist here at Waters Corporation, and today's video quadrupole resolution and mass calibration. I'm going to walk through the procedure for setting the quad resolution and mass scale calibration of your Waters tandem quadrupole mass spectrometer.  

Having valid resolution and mass calibration prior to tuning compounds is important. Because recalibrating may be an effective first step in reestablishing the sensitivity performance of an instrument.  

Fortunately, using `IntelliStart` embedded in your `MassLynx` software, this is a relatively simple task to perform. These calibrations are performed by your water service engineer after they perform routine preventive maintenance and are generally good for about six months. Still, it can be helpful to perform these calibrations as a simple step towards improving system performance.  

If you click on calibration on the tune page, a window will open with information about the most recent calibration. This information includes when the last calibration was performed, the mass range, the scan speeds, resolution settings and ion energies for each quadrupole.  

Each `Xevo` tandem quadrupole model has a specific calibration solution that is typically used for that instrument, you can order the appropriate calibrate solution for your instrument using the part number shown.  

Dilute the calibration solution as directed in the package insert.  

From the sample list page, open the MS console, the MS console will take several seconds to open.  

Once the MS console opens, click on `IntelliStart` under the name of your mass spectrometer model.  

Then click on the `Show Instrument Setup Options` button.  

Select both the instrument resolution and instrument calibration checkboxes and then select Start.  

This `IntelliStart` Screen will tell you the default parameters that will be used when calibrating the instrument provided you with some options for saving and printing the resolution and calibration reports.  

The screen will also tell you which positions on the front of the instrument the calibration solution should be placed.  

We are using a Xevo TQ-S micro as an example. So the same solution is used for the resolution and calibration and therefore reservoir a shown for both.  

Since we now know the default reservoirs for the recalibration solution, we can put it in the appropriate reservoir.  

Once the calibration solution has been attached to the instrument, purged the fluidics for the appropriate reservoir. Once the fluidics indicates that the Purge is complete, by displaying the status as idle, set the valve position to infusion and begin the infusion of calibration solution at 10 microliters per minute by clicking on the start button.  

At the conclusion of the resolution and calibration process, there will be green tick marks to indicate successful calibrations. should either of the procedures fail, this would be indicated with a red X.  

A resolution report can then be reviewed and the calibration window will be updated with the new calibration information.  

The resolution settings and ion energies for each quadrupole set by the new calibration should be used going forward when optimizing or tuning compounds for analysis.   

To review, prior to tuning analytes quadrupole resolution and mass calibration are beneficial first steps and resolution setup and mass calibration are easily performed using automated and tele start routines within `MassLynx`.   

I hope you found this video useful. Learn more about waters LCMS solutions in the clinical laboratory at waters.com/clinical.
