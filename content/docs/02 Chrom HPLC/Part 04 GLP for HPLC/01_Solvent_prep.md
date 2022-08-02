---
authors: Edited by Lenny Lin
categories: Category
date: "2022-01-03"
description: Good practice on solvent preparation
draft: false
lastmod: "2022-01-13"
series: 
tags: []
title: Chapter 01 Solvent
toc: true
editor_options: 
  markdown: 
    wrap: 72
---

Good practice on solvent property.

<!--more-->

## Water

Pass deionized water through an ion exchange bed.

The requirement: 18MΩ resistivity

***Important**: Do not store HPLC grade water in plastic containers.
Additives in the plastic may leach into the water and contaminate it.
Always store HPLC grade water in glass containers*.

## Solvent Line

Each solvent line should be fitted with an inlet filter.

## Solvent Change

Before attempting any solvent change, ensure that the solvent already in the system and
column is compatible with the new solvent.  

**Buffered Phase to Wash or Storage Phase**  
Ensure that the buffer is soluble in the proposed wash or storage phase.

**Normal to Reversed Phase and Vice Versa**  
To convert a normal phase system/column to a reversed phase
system/column, flush with a solvent that is miscible with both the
current normal phase solvents and ideally, the proposed reversed phase
solvents. If the final reversed phase solvents include a buffer, then it
is advisable to move from the 100% methanol flush to a 50% aqueous
methanol flush. For example,

| System         | Solvent Change               |
|----------------|------------------------------|
| Normal Phase   | Hexane/Ethyl Acetate         |
| Flush          | IPA then Methanol            |
|                | Finally 50:50 Methanol/Water |
| Reversed Phase | Buffered Aqueous Methanol    |

<b>Important</b>: There are few columns that can be used in both normal and reversed phase. Check that your column has been engineered to be compatible with both phase types before you attempt any solvent changes.

To convert a reversed phase system/column to a normal phase system/column, follow a similar path to the one listed previously, but in reverse, for example,

| System         | Solvent Change            |
|----------------|---------------------------|
| Reversed Phase | Buffered Aqueous Methanol |
| Flush          | 50:50 Methanol/Water      |
|                | Methanol then IPA         |
| Normal Phase   | Hexane/Ethyl Acetate      |
