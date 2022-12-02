---
authors: null
categories: null
date: "2022-03-17"
description:  
draft: false
lastmod: "2022-07-16"
series: null
tags: [Ion Pair, Trifluoroacetic Acid, TFA, Buffer, Ion Pairs]
title: Avoid Ion Pair Reagents in LC-MS
toc: true
---



<!--more-->

**Ana Coelho**  
I want to perform ion pair chromatography, in LC-MS. Thus, I want to know which ion pair reagents I could use.


**[William Letter](https://faqs.tips/profile/William_Letter)**  

As a general rule, we try to avoid using any / all ion pairing reagents with LC-MS or LC-MS/MS systems. This is based on several decades of use and research. <mark class = "lemon">They tend to contaminate the entire LC source for days, weeks, months to years resulting in higher than normal background levels and additional noise (because they bind to just about everything in the system)</mark>. *TFA is by far one of the most common and worst of the group. Many less experienced users transfer LC methods to the LC/MS systems without first modifying them for use. TFA is grossly overused in HPLC method development (often for no reason at all, accept that the person before them used it! ). It is far too strong an acid for most applications (always use the lowest possible concentration that is needed) and goes bad quickly when exposed to light and air resulting in other contaminates being introduced to the system (very noticeable with a MS system).

The best advice I would share is, if practical, to re-develop your HPLC method to not use ion pairing reagents. Perhaps HILIC or one of the newer highly retentive aqueous columns might be applicable to your samples? This is worth investigating first, before transferring the method to an LC/MS system. When mobile phase acidification is needed, please consider using high purity Formic Acid in place of acetic, TFA or propionic acids. Formic acid is milder than TFA, yet causes no long term problems of contamination. It is also better in the low UV region than Acetic Acid or TFA are, esp for use in tandem with UV detection modes too (DAD-MS, very useful).

If you are unable to find a replacement for the ion pairing reagent, understand that decontaminating the MS source (and LC system, column and flow path) may be both time consuming and costly. Systems that do use it are often put aside as "dedicated LC/MS systems for those samples" (e.g. proteomics), and regular samples are analyzed on other "IP (ion pair) free" MS systems. Also, be cautious about using any fluorinated compounds with an HPLC that uses a modern in-line degasser as many are NOT compatible with those types of compounds (resulting in possible contamination and hardware damage).

Here are a few related articles that may be of interest:  

- "Popular LC/MS and HPLC Volatile Mobile Phase Buffers";   https://hplctips.blogspot.com/2014/06/popular-hplc-volatile-mobile-phase.html  
- "An Often Ignored HPLC & LC/MS Contamination Source. Did you check your Vacuum   Degasser?"; https://hplctips.blogspot.com/2015/08/an-often-ignored-hplc-lcms.html  

**[Navid J. Ayon](https://faqs.tips/profile/Navid_Ayon)**   

What a tremendous excellent explanation Dr. Letter. For unavaoidable reasons we have been using Dimethylhexylamine (DMHA) as an ion pairing reagent in our LC MS system and since joining i have beein seeing its peak in the background for each and every single analysis performed on the system. Hence trying everything else before using ion pairing reagent is a must.  


**[William Letter](https://faqs.tips/profile/William_Letter)**   

DMHA is another stubborn binder. Routine washing with MeOH/DH20 (~ 50/50, or 40/60) with some ammonia (i.e. less than 25 mM ammonium formate or ammonium acetate) may help to slowly remove it over time. If you do use ammonium, then you will also generate ammonium adducts too, but these should go away over time. We alternate the wash solution from acidified (formic) to basic to reduce the level of contamination. Be sure and remove the column used from the system and install a restriction capillary in its place when flushing (put it aside, as it will continue to contaminate the whole system. Label it as noted below). *Remember, columns are consumable items.  

If you have not done so already, please label any/all HPLC columns which are used with IP reagents to keep them separate. Use them only with IP methods. Once exposed to these agents, their surface is often permanently modified/changed so different chromatography results may be obtained using them (IOW: you may not be able to duplicate results run on the column from before it was used with the reagents).

**[Navid J. Ayon](https://faqs.tips/profile/Navid_Ayon)**   

Dr. Letter,  

Thank you so much for such valuable advise. We have been using our column both for IP and without IP analysis and that might explain why we sometimes don’t get reproducible results. I would keep this in mind from now on and try to talk to the supervisor if we can afford to keep columns separate. Also, we have been using 25% methanol as washing solvent. Do you think we should go to a higher methanol percentage. My supervisor is reluctant to go higher as he says that methanol gives a higher pressure. Also I have never used a mild basic solvents to wash the system which is something I can also discuss with the supervisor. Once again thank you so much for you time and help.  

Sincerely,  

Navid  


**[Michael Toner](https://faqs.tips/profile/Michael_Toner4)**   

We have avoided ion pair reagents because of all of the articles on the topic of using ion pairing reagents in a LC-MS. All of them negative. Learn from others mistakes. For HPLC with other detection ion pairing reagents are acceptable but you need to designate the column to limit it for that particular ion pairing reagent.  


**[Markus Christ](https://faqs.tips/profile/Markus_Christ2)**   

Hi Ana,

I can only agree with the previous speakers. Ion pair reagents are usually poison for a LC/MS system. However, there are exceptions. We use e.g. an LC/MS system for the analysis of oligonucleotides and have had very good experiences with HFIP (hexafluoroisopropanol) / TEA (triethylamine). Very nice chromatography and really good signal intensity. However, we only use this system for oligonucleotides, but I cannot say anything about possible negative effects on other analytes.  

Regards  

Markus  


[William Letter](https://faqs.tips/profile/William_Letter) 

A word of caution about using mobile phases with HFIP in them. If your HPLC system utilizes an inline vacuum degasser module, then please avoid using any fluorinated compounds with the degasser module. IN addition to the system wide contamination that may result from using such compounds, we have sometimes seen the chemicals damage the vacuum degasser modules over time.

For more information on this topic: "An Often Ignored HPLC & LC/MS Contamination Source. Did you check your Vacuum Degasser?"; https://hplctips.blogspot.com/2015/08/an-often-ignored-hplc-lcms.html

Markus, you are correct. There are definitely a few key application areas where we do indeed use these nasty IP reagents and oligonucleotides is one of them. In that case, we accept the fact that the system will be contaminated and ideally, you would dedicate it to that application (as the cleanup needed to remove the IP will be very costly and time consuming). When that is the case, we try to use as low a concentration of the IP as possible that still gets the job done in a reliable way.

[Markus Christ](https://faqs.tips/profile/Markus_Christ2) 

Hi Wiliam,

interesting infos related to degassers.

From which manufacturer do you use degasser? We use an Agilent system in case of oligonucleotide analysis. So far (since about 2 years) we had no degasser problems with HFIP.

Regards

Markus

**[William Letter](https://faqs.tips/profile/William_Letter)** 

The cautionary statement applies to all vacuum degassers which use standard 'Teflon AF' degassing membranes or tubing. The manufacturers clearly state these these chambers should not be used with chemicals such as Hexafluoroisopropanol. Special chambers are needed for use with special chemicals. 'We' have services all brands of HPLC vacuum degassers (for > 25 years) and observed an increase in the number of problems when the more porous Teflon AF material were introduced (~ 2003). Teflon AF degassing membranes are found in almost all modern degasser modules (e.g. Shimadzu, Agilent, Thermo, Waters...) and awareness of which types of solvents are safe (and compatible) to use with the specific version of the vacuum chamber used should be reviewed before using them.  

Some manufacturers switched over to the new degassing material exclusively, while others only use it in certain degasser models. While the new degassing material has much higher degassing efficiency (allowing for smaller chamber volumes), the high porosity allows water and many other chemicals to pass into the vacuum system, sometimes resulting in contamination of the mobile phase and/or damage to the degasser. Additionally, fluorinated compounds are soluble with the membrane material. We have seen the degassing membrane leach into the mobile phase and also damage the vacuum system too.  

In HP/Agilent's case, one variation of the latest model G4225A uses Teflon AF. Take precautions if you are using that version, as we do not recommend it be used with any fluorinated compounds, THF, chloroform, hexanes and so on. BTW: Please do not use any model G1379A degasser with THF, chloroform, dichloromethane, heptane and hexanes as the chamber casings are made from PEEK and incompatible with many common HPLC solvents (solvent vapors).  

Most of the older models such as the G1322A and the early versions of the G1379B (not the later models) came from the factory with the less porous standard Teflon membranes (not Teflon AF) and are generally safe for use with many HPLC solvents and chemicals such as HFIP. If you are using one of the std models with pure Teflon inside, then the use of fluorinated compounds carries the conventional warnings only. *Never assume your degasser is working fine. As they age, they all start to break down inside and contaminate the mobile phase. Regular service of the vacuum degasser (~ 4 to 5 years) should be undertaken to keep them clean and operating within specification over time. They require maintenance just like the rest of the HPLC modules, though for some reason (probably because they are "black boxes") are ignored for many years by most users (until they stop working or they contaminate the flow path). In HPLC systems which use inline vacuum degassers, preventative maintenance is critical to maintain reliable operation.  

If you have any specific questions regarding vacuum chamber compatibility, please feel free to send me a private message (through RG), stating the exact brand and model number and I will try to assist you.  



**[William Letter](https://faqs.tips/profile/William_Letter)**   
Markus: Which degasser model(s) do you use on your HPLC?  


**[Markus Christ](https://faqs.tips/profile/Markus_Christ2)** 

William: The system for the oligonucleotide analysis uses a G4204A QuatPump. The pump has a degasser on board.

Regards Markus  

**[William Letter](https://faqs.tips/profile/William_Letter)** 

Hello Markus: The 1290-series G4204A Pump DOES have a built-in vacuum degasser with Teflon AF degassing membranes inside so please be cautious when using IP reagents, any fluorinated solvents, solvents such as THF and chloroform which are not compatible with it (we service a fair number of them which show internal damage from not following these guidelines or from not having them serviced every 5 years). *Agilent's solution is to replace the entire degasser module ($$$$), but can professionally clean and repair the degasser modules in these pumps for a fraction of what they charge.  


**[Michael Toner](https://faqs.tips/profile/Michael_Toner4)**  
William, as an aside, is that service contract on the degass unit extra bucks? We get annual service contracts with Agilent and I have never seen them work on the degass unit.


**[William Letter](https://faqs.tips/profile/William_Letter)** 

Michael, I can not speak for Agilent (I do not, and have never been an employee of Agilent Technologies), but most instrument vendor service contracts cover the specific modules mentioned in the contract. In the case of a 1290-series G4204A pump, with an integrated degasser, the degasser is a component part of the pump, so should be covered.  

- The vacuum degasser modules (integrated and standalone versions) are one of the most neglected parts of the modern HPLC system. They have a limited lifetime and require service every 5 years or so (if well maintained; sooner if abused). As they deteriorate, they contaminate the internal vacuum path which then contaminates the mobile phase (they are a common source of ghost peaks). **We never had these issues when helium sparging was used. The vacuum degassers are "black boxes" to most, which is why most vendors do not repair them until they burst or fail in a dramatic way (instead they 'service' them by replacing the whole degassing module) . In fact, most manufacturers do not train their service engineers to diagnose or repair them (it is not worth their time, which is true, and cheaper for them to just replace the whole degasser module, just as they do with other parts). A <font>&dollar;</font>5K USD "part" is thought to be of little concern when a complete HPLC system costs <font>&dollar;</font>50,000 to <font>&dollar;</font>100,000 USD.  
- Full disclosure to those reading. My company, Chiralizer Services, LLC (USA) has been using, designing, building and servicing HPLC systems for several decades so we have first-hand knowledge of the damaged caused to them from 'real-world' use. We are not affiliated with any of the major instrument manufacturer's, though we do have a division which specializes in the professional servicing of ALL brands of HPLC degasser modules.

**[Holli Palmer](https://faqs.tips/profile/Holli_Palmer)** 

Using HFIP/TEA (or other amine) based IP mobile phases should be fine to use thru an inline degasser if, at the end of the analysis, you flush that mobile phase off the system. So long as the system is not sitting in an HFIP solution, any potential for damage should be minimal.

Of course, flushing mobile phases off of a system quickly should be standard practice, unless you're using straight water/organic mixture. Mobile phases can be acidic, basic, salty, 100% aqueous, etc, all of which can cause their own set of problems if left too long on a system.


**Timothy S Collier**  
The most commonly utilized ion-pair reagents are formic or acetic acids. TFA will certainly suppress ionization, so use sparingly (


## Opposite opinions
**[Marcos Steola](https://faqs.tips/profile/Marcos_Steola)**  

Hi Ana. For LC-MS you must use only volatile reagents. For ion pair you could use trifluoroacetic acid, perfluoropropionic acid or perfluorobutanoic acid. These compounds will work as a ion pair, but take care about trifluoroacetic acid, it is could suppress ionization in your source.

**[Isam Eldin Hussein Elgailani](https://faqs.tips/profile/Isam_Eldin_Elgailani2)** 

Dear Sir. Concerning your issue about the ion pair chromatography reagents that are compatible with LC-MS. The ion-pair reagents for basic samples in LC-MS analysis are supplied as 0.5 M aqueous solutions. The solution can be used as an acidic mobile phase after dilution with the LC solvents (acetonitrile/water or methanol/water) to 5 mM. Since the basic substances are ionized under the acidic conditions, they are facilitated to form an ion-pair.

For LC-MS:

(Trifluoroacetic Acid, Buffer, Ion Pairs) (ca. 0.5mol/L in Water) ………………… 10mL

(Pentafluoropropionic Acid) (ca. 0.5mol/L in Water) ………… 10mL   
(Heptafluorobutyric Acid) (ca. 0.5mol/L in Water) …………… 10mL   
(Nonafluorovaleric Acid) (ca. 0.5mol/L in Water) ……………… 10mL   
(Undecafluorohexanoic Acid) (ca. 5mmol)…………………… 1sample.

I think the following below links may help you in your analysis:

https://www.tcichemicals.com/a-cmn/en/common/support-download/brochure/ion-pair_reagents_for_hplc.pdf

https://pubs.acs.org/doi/abs/10.1021/ac9917240?journalCode=ancham

http://www.waters.com/webassets/cms/library/docs/720002791en.pdf

Thanks




