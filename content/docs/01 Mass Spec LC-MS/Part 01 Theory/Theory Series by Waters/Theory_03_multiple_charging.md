---
authors: Nick Tomczyk, edited by Lenny Lin
categories: null
date: "2022-06-20"
description: 
draft: false
lastmod: "2022-06-20"
series: null
tags: [Waters]
title: 3/7 Multiple Charging
toc: true
---
Fundamentals of Mass Spectrometry provided by Waters (3 of 7)  

In positive ion mode, cations will form bonds with lone pairs of electrons that are located on atoms in the analyte molecule.  These atoms are typically nitrogen, oxygen or sulfur.   

when analyzing small molecules, only one cation bonds with a small molecule to make a single charged ion.  

When analyzing large molecules, there will be more atoms with lone pairs of electron, therefore more charges can be added to the molecule.  

On the mass spectrum, we know that the x-axis represents the mass of the ion divided by the charge the ion is carrying.  If the ion is single charged, the ion will be observed at M+1.  If the ion gets two protons, the ion will be observed at `M+2/2`.  If the charge is 4, the ion will be observed at `M+4/4`.

This is a transcript of the following video.  



<iframe width="360" height="200" src="https://www.youtube.com/embed/CuJRTHvy64k?list=PL6yA4jv5tA-k9_2NVxm5jlzpZV_aW59DT" title="Fundamentals of MS (3 of 7)  - Multiple Charging" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<!--more-->

Hello, my name is Nick and I work at Waters Corporation as a principal analytical scientist. In this short video we're going to talk about multiple charging.  

We learned about the process of ion formation in the Electrospray Ionization or ESI in the electrospray video. In this video, we're going to look at **how ions can be formed with more than one charge**.  We're going to look at multiple charged ions.  

## H Ion with Small Molecules
In positive ion mode, cations, for example, hydrogen ions, will **form bonds with lone pairs of electrons that are located on atoms in the analyte molecule of interest**. These atoms are typically nitrogen, oxygen or sulfur. In the adduct ion video, we looked at the example of UVitex OB, an optical brightener polymer additive. Uvitex OB has a nominal mass of 430, contains two nitrogen atoms, two oxygen atoms and one sulfur atom. All five atoms could be the place where a cation could bond with a molecule. But in practice, other factors, such as relative basicity of each atom, and or any steric hindrances also come into play. In reality, only one cation, Usually a proton in the case of UVitex OB, bonds with a small molecule to make a single charged ion, probably on one of the nitrogen atoms. 

## H Ion with Large Molecules
The story gets more complicated when we start to analyze large molecules using ESI. Large molecules, for example, proteins or synthetic polymers can have many many places where cations could bond and **add to charge the analyte**. The larger the molecule, the more possible **sites of cationization**, and the more charges can be added to its structure, for the more charge an ion can carry.   

## The Effect on the Mass Spectrum  
Let's consider what effect multiple charging will have on the mass spectrum. We know that the x-axis in a mass spectrum represents the mass of the ion divided by **the charge the ion is carrying**. This is very simple for single charged ions, because that means the mass is divided by one. Each mass spectral peak represents the mass of the ion. If **the charge on the ion** is greater than one, the m/z [m over z] value of the peak no longer represents the mass of the ion. The peak is shifted to a lower valley depending on the number of charges present. 

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 112006.png" style ="float: left" HSPACE="10" VSPACE="10"/>
In the case of a molecule that has a massive 1000,  if it becomes an adduct ion getting one proton, then its mass will be 1001 and the charge will be one. So **the ion will be observed at m over z 1001**. If the same molecule becomes an adduct ion getting two protons, its overall mass will be 1002, but the charge will also be two. So the ion will be observed at 501 and so on. With three protons added, the mass is 1003 and the charge three, so the ion observed at 334.3. And with four protons added, the mass is 1004, the charge is 4, and the ion is m over z 251.  

If the same compound is observed to have different numbers of charges within the same spectrum, it is described as having different charge dates. This phenomenon of multiple charges can be very useful, because it enables us to analyze very high mass molecules, bringing them within the mass range of the mass spectrometer. 

## C-13 Isotope
The presence of carbon 13 isotopes and other atoms with isotopes in a molecule means that each analyte compound does not produce a single individual ion, but a cluster of ions depending on the distribution of isotopes present. You can learn more about this in the video about isotopes. Information about the number of charges on an ion can also be derived by examining the isotope clusters for that ion. However, we have to be careful because reasonably high mass resolution is usually required to be able to accurately distinguish the lower intensity isotopes. And often quadrupole mass spectrometers do not deliver sufficient mass resolution for the user to see the isotope pattern clearly.   

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 112858.png" style ="float: left" HSPACE="10" VSPACE="10"/>
The gap between the individual ions within an isotope cluster tells us the charge state of an ion. We'll look at some isotope model classes to see how. Here a single charge isotope cluster has a gap of one unit between adjacent ions. The isotope cluster for the same molecule with a double charge has a gap of half a unit between the adjacent ions. And for an isotope cluster with triple charge, the gap is 0.33. Mathematically the gap between the adjacent ions in an isolated cluster is given by one divided by the charge of the ion. So using this logic, we can deduce that a quadruple charged ion and have a gap of 0.25 units between the adjacent ions of the cluster.  
<br>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 113039.png" style ="float: left" HSPACE="10" VSPACE="10"/>
In this example, the data was acquired at a high resolution mass spectrometer. Here we can see the extremely complex spectrum of a polymer sample called polyethylene Glycol, or PEG. The structure of PEG has lots of sites where protons and other cations can join the molecule because there are many oxygen atoms regularly spaced around the polymer chain.  PEG readily forms ions with multiple charges. If we take a closer look at some of the ion clusters within the spectrum, we can start to learn more about the different charge states present.   
<br>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 113438.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 113634.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 113752.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 113847.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-06-23 113945.png" style ="float: left" HSPACE="10" VSPACE="10"/>
Here the ions are one unit apart, so, they must have a single charge, whereas here the gap is half a unit, so they must have a double charge. In fact, in this particular spectrum, we can distinguish charge states from one plus all the way up to seven plus. The gap between the ions in this cluster is approximately 0.14, which is one divided by seven. In the case of mass spectrometry of large biomolecules, it is possible for even higher numbers of charge states, for example, proteins with masses around 150,000 Daltons and have charges in excess of 20.