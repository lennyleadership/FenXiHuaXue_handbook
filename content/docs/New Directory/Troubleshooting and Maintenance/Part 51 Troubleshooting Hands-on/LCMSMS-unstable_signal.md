---
authors: edited by Lenny Lin
categories:
date: "2022-07-07"
description: null
draft: false
lastmod: "2022-07-07"
series:
tags: []
title: LC-MS/MS unstable Signals
toc: true
---




<!--more-->

## Case #01

**Situation**:  
I am currently working on the quantification of certain terpenes/alkaloids compounds in plants. My laboratory has been using SCIEX 6500 triple Quad and recently acquired Thermo TSQ Quantiva triple quad. We have established many methods in SCIEX that worked satisfactorily and now trying to transfer the method established in 6500 to Quantiva. However, I have been having unstable signal problems in optimizing the condition in TSQ Quantiva.

The system I am using is a Thermo Dionex Ultimate 3000 UPLC and TSQ Quantiva triple quad. I have already tuned my compounds in Quantiva and manual tuning by infusing the standard compounds into the MS seems normal with stable signal of RSD<15%. However, when I tried to setup the whole program with LC and MRM conditions, the signals of all my target analytes fluctuates, say every 5-10 injections, there would be one injection that the signals of all analytes became nearly half. But when I tried to do replicate injections of reserpine, everything seems alright.

I have checked the UPLC part but the flow rate, pressure, etc looks normal. I have also cleaned the source, needles etc, but that doesn't improve much. Previously I have got relatively more stable signal with the same conditions for my target analytes, but then after doing replicate injections for nearly 60 times, the instrument never became stable again. I have tried all the other analytes that worked previously but still everything went unstable except reserpine.

I have been encountering this problem for several months but still cannot solve it.

**Solution**:  
The injections that are fluctuating; are those injections of solvent standards or samples?  

When transferring the method, did you take into account that the SCIEX 6500 is a more sensitive instrument than the Quantiva? Maybe you are trying to measure at a level that is just to low for the quantiva?  

    Point: concentration is too low.

**Solution**:
Our lab recently got a Quantiva. We started having issues where we would get a linear curve at low concentrations and it would bend over at higher concentrated standards.

Im not sure if this is relatable or not, but what fixed this issue was **recalibrating the electron multiplier**.  

I've heard from thermo techs that the Quantiva detector isn't the greatest, it needs 'broken in' and furthermore, it will probably need replaced yearly. But I'm assuming that your Quantiva is new, and I would try recalibrating the multiplier monthly.  

Hope this might help.

EDIT: just extra stuff I was thinking about. With our Quantiva, we have to clean the ion transfer tube like every 3 days. It makes a HUGE difference in signal strength. It's actually really frustrating. They made the transfer tube different in this model (wayyy bigger orifice (to try and get more ions into the detector?)) and it totally wasn't an improvement.

I personally don't recommend the Quantiva for the above reasons, we have multiple TSQ Vantage from thermo and they work more reliably than this new instrument with the same sensitivity.  

    Point: recalibrate the electron multiplier

**Solution**:  
We have been recalibrating the EM once every three months. But the signal is still unstable even after the reaclibration. Our ion tube has to be cleaned quite often too, even when we were now just injecting pure standard for stability checking.  

Recently it was found that the signal became stable when the divert valve is not used to divert sample to waste, i.e. all samples go directly to MS. When diverting the early eluting portion to waste, the signal became unstable. The divert valve has been replaced twice and didn't seem to solve the problem.  

    Point: divert valve is tricky

**Solution**:
You mentioned earlier that using the divert valve early in the run seemed to introduce the variability. Does your gradient include acetonitrile or source use the fused silica sample tube?  

We've had problems in the past on a Quantum with the fused silica drying out during the run (with a divert valve and heat on) and the polyimide coating "growing" out of the needle causing unstable spray. Replacing that with the stainless sample tube stopped the required weekly trim.  

    Point: the divert valve

**Solution**:

problems like this can be solved by making sure that all the basic things - fresh standards, clean spray shields, sometimes salt buildup on other parts of the ion-source, etc. - are taken care of. Then you might have to dig deeper, so maybe it's time to get in touch with a service engineer.

    Point: fresh standards, clean spray shields, builtup salt.





**Reference**:  
https://www.chromforum.org/viewtopic.php?t=49674
