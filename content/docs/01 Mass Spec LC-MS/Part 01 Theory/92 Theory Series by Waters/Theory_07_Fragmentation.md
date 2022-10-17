---
weight: 7
title: Fragmentation
authors: "Nick Tomczyk, edited by Lenny Lin"
categories: null
tags: [Waters]
description: 
draft: false
date: "2022-06-20"
lastmod: "2022-06-20"
series: null
toc: true
---

Fundamentals of Mass Spectrometry provided by Waters (7 of 7)    

Fragmentation occurs at CID. The CID yields fragments using relatively low energies. The drawback of the CID is its difficulty to predict the results for complex molecules. 

The CID will <u>accelerate molecules into an inert gas</u> often argon or nitrogen, the molecules hit the gas and energy is transferred, causing the bonds to break.

<!--more-->
---
This is a transcript of the following video.  
<iframe width="360" height="200" src="https://www.youtube.com/embed/ESKpOcjF8QM?list=PL6yA4jv5tA-k9_2NVxm5jlzpZV_aW59DT" title="Fundamentals of MS (7 of 7) - Fragmentation" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Hello, my name is Nick and I work at Waters Corporation as a principal analytical scientist. And in this short video, we're going to talk about fragmentation.   

## What does CID work?
As well as measuring the `m over z` of whole molecules, certain mass spectrometers can be used in such a way as to break apart or fragment molecules and measure the m/z of these fragments. This information can be used to try and understand or `elucidate the connectivity within the molecule`. Or it can be used to increase the specificity of analysis by measuring the precursor and fragment masses. To do this, we must understand how molecules break apart in a mass spectrometer. Most mass specs use `Collision-Induced Disassociation` or CID, which <u>yields fragments</u> using relatively low energies. CID is common in mass spec because it's relatively easy to implement, easy to use, but it can be difficult to predict the results for complex molecules.   

In very basic terms, <u>the CID will accelerate molecules into an inert gas often argon or nitrogen, the molecules hit the gas and energy is transferred, causing the bonds to break</u>. It's not unlike breaking a Lego model by throwing marbles at it. 


## A Bond Energy Table
<div class ="row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 182136.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 182303.png" style ="float: left" HSPACE="10" VSPACE="10"/>
</div>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 182447.png" style ="float: left" HSPACE="10" VSPACE="10"/>  

In this example, the verapamil molecule with m/z of 455, had been fragmented in the mass spec and the fragmentation spectrum required is shown. You can see some precursor remaining and also <u>a number of ions at lower m/z and various intensities</u>. Begin to make sense of this fragmentation spectrum, we need to look at the structure of the verapamil molecule.  

As you can see, the molecule is very simplistically, two aromatic rings joined together by a chain containing carbon and nitrogen atoms. The most obvious sites that you would expect this molecule to break along this connecting chain. However, not all bonds are equal, we can estimate the strength of each bond in this molecule, and therefore how easy or likely it is for it to break by looking at <b>a bond energy table</b> like this. 

<div class ="row">
<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-08-16 111308.png"/>  
</div>
By comparing the energies of the various bonds, we can suggest that `the bond most likely to break` is the <b>N-C</b> bond here, followed by the <b>C-C</b> bond and then the <b>C-O</b> bond. The energy required to break aromatic ring is normally too high for CID. If you apply this idea in the future, remember this simplistic model only the actual bond energies are affected by other adjacent groups of atoms. So don't be surprised at the results you obtained from real molecule definitely your prediction. 

<div class = "row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 182630.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 182845.png" style ="float: left" HSPACE="10" VSPACE="10"/>
</div>

By using this idea, we can predict that we might see fragment ions at 165, 300, 194 and 289. Fragmentation spectrum actually looks like this. And we can see that we did predict both Fragment A and B as shown. But we see no evidence of the others in this spectrum. As I mentioned before, many other factors come into play when `fragmenting molecules`, including but not limited to the location of bonds within the whole molecule and the specific location of the adduct. The relative intensity of fragments is linked to the likelihood of a bond or bonds in breaking and in turn is linked to bond energy. Bond energies for <b>C-N</b> bond is in the order of 293 kilojoules per mole. And for a <b>C-C</b> bond around 347 kilojoules per mole (KJ/mole).   

<div class ="row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 183104.png" style ="float: left" HSPACE="10" VSPACE="10"/>
If you look at the fragmentation spectrum, you can see that Fragment B is four to five times less intense than Fragment A. And this is because more energy required to break that <b>C-C</b> bond and so it just happens less often. 
</div>

## Fragmentation of Peptides
All molecules will behave differently, but basic chemistry rules governing bond energies will always remain the same. 
<div class ="row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 183417.png" style ="float: left" HSPACE="10" VSPACE="10"/>  
So it is possible to predict what <u>the fragmentation spectrum</u> may look like. For example, peptides or linear chains of amino acids linked by amide bonds. Under CID, most of these amide bonds will fragment equally.   So typically you get a ladder like <u>fragmentation spectra</u> like this. 
</div>
By using simple rules and chemistry knowledge, we can use <u>fragmentation spectra</u> to help us identify unknown compounds or increased confidence in the identification when screening. A basic understanding of the rules is important but like many things in mass spectrometry, many software packages help with data interpretation.
