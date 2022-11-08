---
authors: edited by Lenny Lin
categories:
date: "2022-07-07"
description: null
draft: false
lastmod: "2022-07-07"
series:
tags: []
title: Problem with one Analyte Response
toc: true
---

**Solutions could be**:  
Do an infusion test.  
Modify the gases.  

**Lesson learnt**:  
IS should mimic the analyte and therefore compensates for the variability you observe.  
matrix effects are tested on a limited number of injections, and accumulating effects may not be visible during the validation.  

<!--more-->

**Situation**:  
We have validated method for FDC (2 analytes) by LC-MS/MS. But when we initiated `subject sample` analysis, one of the analyte is showing variation in response due to which 4 subjects out of 12 analysed until now need to be repeated due to results for this analyte is not within batch acceptance criteria. There are total 64 subjects to be analysed. We have checked all possibilities for this response variation but there is no change.  
I think there is some change in the LC-MS/MS parameter for this molecule; therefore I want to know can I tune or optimize the LC-MS/MS parameters for this molecule in-between the analysis and continue further analysis of remaining subject after carrying out a PA batch in partial method validation or how to go about it.  


**Solution #01**  
I recommend to do an infusion test to determine the extent of the problem. Apparently, you have an ionization effect, therefore by infusing your drugs of interest along with the internal standards and injecting a QC sample versus a clinical sample, you will be able to see any ionization differences with time (maybe 30 minutes is sufficient). This will allow you to demonstrate the method is functioning properly (or not) without consuming a high volume of the clinical samples.

From past experience, I expect that modifying the gases will not solve your problem.


**Solution #02**  
1. What internal standard are you using: stable-labelled, structural analogue, other ?  
A1: No, internal standard is not stable-labelled, structural analogue, but the internal standard response throughout analysis is reproducible with excellent % CV.  
B1: Which is actually a problem: your IS noes not mimic the analyte and therefore does not compensate for the variability you observe.

2. What type of sample preparation are you using: protein precipitation, liquid-liquid extraction, solid phase extraction ?  
A1: sample preparation is by liquid-liquid extraction method.  

3. Any "strange result" in the validation ?  
A1: No, method validation was extremely smooth and satisfactory with hardly 3 to 4 QCs out of acceptance criteria throughout validation.  

4. What do you mean by "variation in response" of the analyte: do you mean that for your QC samples, for a same concentration you get a very different response for the analyte, while the response for the internal standard is stable ? And how much "variation" do you see ?  
A1: Variation in response means in system suitability test (prepared in matrix) first five injection shows reproducible response but the sixth injection shows different response for only that analyte while another analyte and IS shows good reproducibility. Similar results are observed during `subject analysis` after 4 to 5 injections there is change in response for that particular analyte and due to which we have to reject the batch (e.g. in cc and QC sample shows accuracy of 70 or 140 % for any of the in-between standard/QC sample).  
B1: This looks like your ion source needs some injections to stabilise. May be due to matrix effects (endogenous components accumulating on the column and getting released gradually thereafter) or due to a sort of conditioning. Does the response still vary afterwards, or does it get stable (but at a different level) after these first 5-10 (or more) injections ? If it does get stable afterwards, you may need to start your run with some injections of blank samples, and pay attention if there is an interruption in your run and you resume injections after some time.  
A2: We have carried out matrix effect during validation and also for bulk cc and QC sample preparation for subject analysis which was satisfactory for all analytes and IS.    
We had to inject at least 25 SST injections to stabilize the system before injecting six injection for the analysis batch which was not the case during method validation.  
If there is interruption in run it should have effected the response for another analyte also which is not seen here.  
B2: True. But matrix effects are tested on a limited number of injections, and accumulating effects may not be visible during the validation.  
No. Whatever the cause for your problem, ionisation is an analyte-specific issue. You may have problems with one analyte and not with the other. This is actually your case: you have problems with one analyte, but not with the internal standard.  


5. What LC/MS/MS parameter do you plan to change ?  
A1: I planning to change slightly Source parameters of LC/MS/MS and not the compound parameters because I think gases need to be optimized.  
B1: This could indeed improve the situation, and just running a P&A run could be acceptable. However if you saw no problem during your initial validation, there are chances the P&A run will pass too. How do you plan to make sure that your new parameters will improve the situation, before you re-start sample analysis ?  
A2: I am planning to optimize instrument parameters (Gases) and observe the response for both analyte and IS by injecting SST solution, if the system gates stable in minimum number of injections, I will analyze one PA batch in PMV and then proceed for subject analysis.  
I want to know can I continue with subject analysis from no 13 as I have already analysed 12 out of which 4 needs to be repeated or I will have to start from first subject as instrument parameters will change from 13th subject.   
B2: As you have a clearly identified analytical issue I would re-analyse all samples after optimisation, if the situation improves. Will you be doing incurred sample reanalysis ? If some subject samples are affected also in the runs you have validated so far, you may end up failing ISR. Better be on the safe side, if you still have enough samples.  

**Reference**  
https://forum.bebac.at/mix_entry.php?id=5337#p5337
