---
authors: edited by Lenny Lin
categories:
date: "2022-07-07"
description: null
draft: false
lastmod: "2022-07-07"
series:
tags: []
title: LC-MS/MS No Signal
toc: true
---






<!--more-->

## Case #01

**Situation**: I'm playing with waters TQ detector for pesticide analysis.
I washed the column with 50% ACN to 90% ACN overnight and somehow there is now no analyte peaks.
I tried for many types of standard, and only background noise can be obtained.
Then, I checked the flow rate for washing column, and it is 0.5 ml/min. I am not sure if it is too high, cause I found there is a little solution leak from the top of probe sometime. ( Wondering if it is really a leakage, maybe I can take a photo if it comes again...)
I also used tune page with high selective analyte but again no signal observed.

**Solution**:  
1) verify the system is in working condition and the instrument tune report ion abundances and peak widths should match approximately the same settings as when the system was first installed or was in working order.  
2) Did you guys perform a recent tune? This is your starting ground, if not you could have some sort of problem going on with the detector or quadrupoles or something else and would require a complete diagnostics by the service engineer.  
3) Are you guys maintaining vacuum?   
4) Did you prepare a fresh tuning solution?  
5) How is your gas supply, do you have enough collision cell gas and nebulizer gas? 
6) Is that an ESI source in positive polarity?  

**Solution**:  
I finally called the engineer for help.
The problem is that I really set flow rate too high, which making the inlet transfer tube broken and get off from the probe. So it means there is no injection to MS and of cause no signal can be found.
Anyways, 0.5 ml/min is too high for uplc-msms system, that's what I learn.

**Reference**: https://www.chromforum.org/viewtopic.php?t=22478

## Case #02
**Situation**:  
JetStream ESI Agilent 6470a coupled with Agilent 1260 Infiniti.  

The signal is completely gone. It doesn't matter where the liquid comes from in mass-spec - from HPLC, through the tuning line or directly from the syringe - the effect is the same - zero signal. Tuning mixture, chloramphenicol, reserpine, polytyrosine - nothing is detected.  

At the same time, the nebulizer forms a good spray. What could be the problem?  

P.S. It is interesting that the capillary current does not change much and, regardless of the presence or absence of a spray, it remains about 2000 nA. Could this be an isolator problem?  

**Solution**:  
Did you check the Vchamber and Vcap? Did you try to replace the capillary? 


## Case #03  
**Situation**:  
- single quad, and sorry forgot the details. The instrument is Agilent LC-MS (1260 HPLC and 6120 MSD). Other details,
- cleaned the source, corona needle with mesh and IPA:water 50:50, every day or before every sequence  

- checked the nebulizer needle if the tuning mix drops are coming out and also if the spray is coming out   

- changed the column to see any issue with the column   

- changed to a different standard material to see any issue with the sample itself   

- changed the solvent bottles to new solvent mix  

- refilled the tuning mix bottle to a new one
After running the APCI tuning checktune, autotun -dual on our HPLC-MS, the MSD cannot find the signal. They more look like noise and fails the tuning.

**Solution**: 
1) Do you get any error message from the software, something like: "Difficulty with spray chamber electronics"?   
2) If your spray chamber settings are okay, you have verified that a sufficient amount tuning mix makes it to the nebulizer and you're using a fresh bottle of the correct mix, then I would also make that the corona needle is clean and sharp, the nebulizer is adjusted correctly and the spray shield is clean.








