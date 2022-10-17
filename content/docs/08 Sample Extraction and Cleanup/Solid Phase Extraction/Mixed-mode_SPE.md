---
authors: Stephanie J. Marin, Ph.D., edited by Lenny Lin
categories: null
date: "2022-05-07"
description:
draft: false
lastmod: "2022-06-24"
series: null
tags: null
title: When should I choose a mixed-mode SPE?
toc: true
---


<!--more-->

Mixed mode Solid Phase Extraction (SPE) phases have become very popular for sample clean-up prior to analysis using mass spectrometry. Having the capability to retain compounds by two modes of interaction during SPE is useful when a large number of analytes with different properties are of interest.

**Most mixed mode phases are bonded silica or polymeric reversed phase materials with an ion-exchange group bonded to it**. Cation exchange phases like [EVOLUTE EXPRESS CX](https://www.biotage.com/product-page/evolute-express-cx) usually have a negatively charged sulfonate group covalently bonded to the reversed phase backbone. Anion exchange phases like [EVOLUTE EXPRESS AX](https://www.biotage.com/product-page/evolute-express-ax) typically have a positively charged quaternary ammonium group. Figure 1 shows the structure of both EVOLUTE EXPRESS CX and EVOLUTE EXPRESS AX.

<div class = "row">
  <figure>
  <img width ="360" height= "200" src = "/docs/images/SP-EVOLUTE-EXPRESS-CX-300x250.jpg" style ="float: left" HSPACE="10" VSPACE="10"/>
  <img width ="360" height= "200" src = "/docs/images/SP-EVOLUTE-EXPRESS-AX-300x246.jpg" style ="float: left" HSPACE="10" VSPACE="10"/>
<b>Figure 1</b>: Chemical structures of both cation exchange phase EVOLUTE EXPRESS CX and anion exchange phase EVOLUTE EXPRESS AX.
  </figure>
</div>

These are strong acid or strong base cation or anion [exchange phases](https://en.wikipedia.org/wiki/Ion-exchange_resin), meaning that the sulfonate or quaternary ammonium groups remain charged over the entire pH range.

## So, you’re asking – what does these charges do for me?

It allows you to adjust the pH of your sample, based on the pKa of the analytes of interest, to make them positively or negatively charged so that you can retain them by cation or anion exchange in addition to (or instead of) reversed phase. Ion exchange is a much stronger retention mechanism and allows the use of more aggressive wash steps to clean up the sample. It is especially good for removing hydrophobic interfering compounds with a strong organic wash. If all of your analytes of interest are retained by cation or anion exchange, 100% methanol, acetonitrile or hexane can often be used as the organic wash without eluting your analytes of interest.

If all of your compounds could be positively or negatively charged – life would be easy!

## Basic compounds

For positively charged (basic) compounds, you just adjust your sample pH to 2 pH units below the pKa (usually with an acid). This turns the positive charge of the molecules “on” so they can be retained by cation exchange. Load the sample onto the cation exchange SPE phase, wash with acid (often the same solution you used to pretreat your sample), wash with 100% organic solvent, then elute with basic organic solvent at least pH 2 units above the pKa of your sample. This turns the charge of your molecules “off” and disrupts the ion exchange retention, releasing the compounds from the SPE phase.

## Acidic compounds

Anion exchange for acidic compounds works in reverse. Adjust the pH to 2 units above the pKa, usually with a base, to negatively charge the compounds, load, wash with base, wash with organic solvent, and elute with acidified organic solvent to “turn off” the negative charge.

Super simple!

Sigh. Life is usually not that simple. If only every assay had compounds that could be all positively or negatively charged and that was the only interaction with the SPE phase. Unfortunately, most analytical methods have groups of acidic, basic and neutral compounds that may have a positive or negative charge, or be neutral at a single pH. Also, part of the molecule could be charged and be retained by ion exchange while another part of the molecule can exhibit reversed phase retention.

What’s an analytical chemist to do? That’s where mixed mode SPE can help you out. Because these phases are mixed mode, a polymeric reversed phase material with cation or anion exchange moieties bonded to it, you have the ability to retain compounds by ion exchange and reversed phase! This is great for large panels with acidic, basic and neutral compounds.

## Here’s the general strategy for a polymeric reversed phase ion exchange SPE method, step-by-step:

1. Know your compounds! Look up the logP and pKa of the compounds in your assay. I can’t emphasize this enough! If you don’t know the properties of the compounds, you don’t know how they will be retained, and your method development will take a lot longer.  
2. If there are a large number of basic analytes that can be positively charged, proceed with *<font color ="blue">mixed mode cation exchange</font>*. If you have more acidic compounds that can be negatively charged, move forward with *<font color ="blue">mixed mode anion exchange</font>*. Some compounds will be charged and some will be neutral. That’s ok. You’re using both mechanisms for retention.  
3. Find the pH where the majority of your compounds will be either positively or negatively charged (remember the pH “rule of 2”). The remaining compounds will be neutral. This may mean adjusting to a very low or very high pH to ionize the majority of compounds. This is ok – polymeric phases are stable over the entire pH range. Make sure your all of your compounds are stable at the pH you choose.  
4. Prepare a solution and pretreat your samples so that they are at the pH where the majority of your analytes will be positively or negatively charged.  
5. Load samples onto the correct mixed mode SPE phase.  
6. Do an aqueous wash. Often the solution used to pretreat the sample will work well for the aqueous wash step, but sometimes other washes will need to be evaluated. Just make sure you don’t move too far from the pH where your samples are charged, or you may "turn off" the charge and elute them.
7. Do an organic wash. Try several washes with increasing amounts of organic:aqueous solvent and see what happens to your compounds retained by reversed phase. Chooses the highest ratio of organic to aqueous that provides good recovery of all compounds.
8. Dry the columns for several minutes.
9. Elute with basic or acidic organic solvent. Some elution solvents that work well with EVOLUTE EXPRESS CX are combinations of *<font color ="blue">methylene chloride or ethyl acetate with 2-propanol</font>* or *<font color ="blue">methanol and 2% ammonium hydroxide</font>*, or *<font color ="blue">methanol or acetonitrile with 2% ammonium hydroxide</font>*. For EVOLUTE EXPRESS AX, *<font color ="blue">methanol or acetonitrile with 2-5% formic acid</font>* is a good starting point.
10. Dry the samples under nitrogen, reconstitute, and analyze.


[Source: Biotage Blog](https://sampleprep.biotage.com/blog/when-should-i-choose-a-mixed-mode-spe)

<style type = "text/css">
.row {
  margin-left:-5px;
  margin-right:-5px;
}

.row::after {
  content: "";
  clear: both;
  display: table;
}

figure {
  text-align: left;
  font-style: italic;
  font-size: smaller;
  text-indent: 0;
  margin: 0.5em;
  padding: 0.5em;
}

</style>
