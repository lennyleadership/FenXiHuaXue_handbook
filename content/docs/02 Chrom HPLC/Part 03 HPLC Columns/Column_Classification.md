---
authors: edited by Lenny Lin
categories: Category
date: "2022-01-03"
description: Column Classification System
draft: false
lastmod: "2022-01-20"
series: 
tags: []
title: Column Classification System 
toc: true
---

<figcaption><b>Figure </b>: </figcaption>

<img src = "/docs/images/"/>

Columns are characterized by 4 column parameters, which are determined with 3 simple, fast, repeatable and reproducible chromatographic methods. More information can be obtained in the test procedure manual (below), ranking procedure based on F-value (below) and freeware.  

The 4 column parameters are:  
1) the retention factor of amylbenzene, <font color = "blue">_k' amylbenzene_</font>, 
2) the relative retention factor of triphenylene/o-terphenyl, <font color = "blue">_rk' triphenylene/o-terphenyl_</font>,  
3) the relative retention factor of benzylamine/phenol at pH 2.7, <font color = "blue">_rk' benzylamine/phenol pH 2.7_</font> and   
4) the retention factor of 2,2'-dipyridyl, <font color = "blue">_k' 2,2-dipyridyl_</font>.

<!--more-->

## Test Procedure Manual

### 1. Introduction

To characterize a column, three chromatographic methods have to be carried out in a defined order of execution (A-B-C). A slight adaptation of the method was introduced in 2006, by using a buffered mobile phase for the analysis of 2,2'-dipyridyl and by analyzing uracil only in the third method. This allows to obtain a faster elution of 2,2'-dipyridyl and a more consistent determination of the dead volume.

<table style="width:93%;"><colgroup><col style="width: 18%" /><col style="width: 35%" /><col style="width: 18%" /><col style="width: 18%" /></colgroup><thead><tr class="header"><th><p>Method</p></th><th><p>Mobile Phase</p></th><th><p>Sample</p></th><th><p>Column Parameter</p></th></tr></thead><tbody><tr class="odd"><td><p>A</p></td><td><p>Methanol - Water - 0.2M Potassium phosphate buffer pH 2.7 (34:90:10, w/w)</p></td><td><p>Benzylamine<br />
phenol</p></td><td><p>rk' benzylamine/phenol</p></td></tr><tr class="even"><td><p>B</p></td><td><p>Methanol - Water - 0.2 M potassium phosphate buffer pH 6.5 (34:90:10, w/w)</p></td><td><p>2,2'-dipyridyl</p></td><td><p>k' 2,2'-dipyridyl</p></td></tr><tr class="odd"><td><p>C</p></td><td><p>Methanol - Water (317:100, w/w)</p></td><td><p>Uracil<br />
amylbenzene<br />
o-terphenyl<br />
triphenylene</p></td><td><p>k' amylbenzene<br />
rk' triphenylene/o-terphenyl</p></td></tr></tbody></table>

### 2. Reagents & samples

Samples and chemicals should be of analytical grade, solvents of HPLC grade: methanol, water, potassium dihydrogen phosphate, dipotassium hydrogen phosphate, phosphoric acid.

List of samples: benzylamine, phenol, uracil, 2,2'-dipyridyl, amylbenzene, o-terphenyl and triphenylene.

Mobile phases must be prepared by weight (w/w). It is necessary to use HPLC grade solvents.

Preparation of the potassium phosphate buffer pH 2.7: Make 0.2 M potassium dihydrogen phosphate solution (27.22 g $\small{\textrm{KH}}_2\small{\textrm{PO}}_4$ in 1000 ml of water) and adjust the pH to 2.7 with 0.2 M $\small{\textrm{H}}_3\small{\textrm{PO}}_4$ .

Preparation of the potassium phosphate buffer pH 6.5: Make 0.2 M potassium dihydrogen phosphate solution (27.22 g $\small{\textrm{KH}}_2\small{\textrm{PO}}_4$ in 1000 ml of water) and adjust the pH to 6.5 with 0.2 M diPotassium hydrogen phosphate solution (34.84 g K2 HPO4 in 1000 ml of water).

All mobile phases should be degassed properly before use.

| Method | **Mobile Phase Composition**                                              |
|:-------|:--------------------------------------------------------------------------|
| A      | methanol - water- 0.2 M potassium phosphate buffer pH 2.7 (34:90:10, w/w) |
| B      | methanol - water- 0.2 M potassium phosphate buffer pH 6.5 (34:90:10, w/w) |
| C      | methanol - water (317:100, w/w)                                           |

### 3. Preparation and analysis of the samples

For some of the samples it is recommended to prepare stock solutions, which can be diluted to obtain the correct final concentrations.

| Method | Sample Composition                                                                                     |
|:-------|:-------------------------------------------------------------------------------------------------------|
| A      | 5 mg of benzylamine and 5 mg of phenol in 10.0 ml of mobile phase A                                    |
| B      | 3 mg 2,2'-dipyridyl in 10.0 ml of mobile phase B                                                       |
| C      | 0.1 mg uracil, 7 mg amylbenzene, 0.2 mg o-terphenyl and 0.02 mg triphenylene in 10.0 ml mobile phase C |

*Chromatographic conditions:*

Flow rate: 1.0 ml/min

Injection volume: 20 µl

Column temperature: 40 °C ± 0.5 °C

Detection: 254 nm

*Analysis*

-   The chromatographic tests have to be carried out in the fixed order A-B-C.

-   Start with mobile phase A; flush the column for 90 minutes with mobile phase A in order to equilibrate the system.

-   Inject three times 20 µl of sample A. Depending on the column, one chromatogram takes about 20 to 30 minutes.

-   Switch to mobile phase B. Flush the column for 90 minutes with mobile phase B in order to equilibrate the system.

-   Inject three times 20 µl of sample B. Depending on the column, one chromatogram takes about 40 to 100 minutes. On some columns no dipyridyl peak can be observed. When no peak is observed within 100 minutes, a fixed value has to be used in the calculations.

-   Switch to mobile phase C. Flush the column for 90 minutes with mobile phase C in order to equilibrate the system.

-   Inject three times 20 µl of sample C. Depending on the column, one chromatogram takes about 20 to 30 minutes.

-   Wash the column according to the manufacturers' recommendations.

### 4. Calculation of the column parameters

First, calculate the parameter values for each injection, then calculate the mean value for the three injections.

*Method A:*

\- the relative retention factor of benzylamine/phenol at pH 2.7, *<font color = "blue">rk' benzylamine/phenol pH 2.7</font>*  

$
\frac{Tr(benzylamine) - Tr(uracil)}{Tr(phenol) - Tr(uracil)}
$

*Method B:*

\- the retention factor of 2,2'-dipyridyl, *<font color = "blue">k' 2,2-dipyridyl</font>*  

$
\frac{Tr(2,2'-dipyridyl)-Tr(uracil)}{Tr(uracil)}
$


*Method C:*

\- the retention factor of amylbenzene, *<font color = "blue">k' amylbenzene</font>*  

$
\frac{Tr(amylbenzene)-Tr(uracil)}{Tr(uracil)}
$
 

\- the relative retention factor of triphenylene/o-terphenyl, *<font color = "blue">rk' triphenylene/o-terphenyl</font>*  

$
\frac{Tr(triphenylene) - Tr(uracil)}{Tr(o-terphenyl) - Tr(uracil)}
$


## Column Classification System Ranking

**Ranking based on F-Value** 

All columns in the database are characterized by 4 column parameters: the retention factor of amylbenzene, <font color = "blue">k' amylbenzene</font>, the relative retention factor of triphenylene/o-terphenyl, <font color = "blue">rk' triphenylene/o-terphenyl</font>, the relative retention factor of benzylamine/phenol at pH 2.7, <font color = "blue">rk' benzylamine/phenol pH 2.7</font>, the retention factor of 2,2'-dipyridyl, <font color = "blue">k' 2,2-dipyridyl</font>. 

The column classification starts with the selection of a reference column. As all columns are characterized by 4 column parameters, a classification of RP-LC C18 columns, based on the similarity of their column parameters to the parameters of a reference column, can be obtained. In order to do so an F-value has been introduced. The F-value expresses the similarity of a column to the reference column. The smaller the F-value, the more similar is the column to the reference column.

<font color = "blue">The column classification system classifies all columns from the database according to their F-value</font>. The smaller the F-value, the higher the column is positioned in the classification. This means that columns with a selectivity similar to the reference column are found high in the ranking (= high ranked columns ). 

The larger the F-value, the lower the column is positioned in the classification. This means that columns with a selectivity different from the reference column are found at low positions in the ranking (= low ranked columns ). 

**Conclusion: High ranked columns are columns with a selectivity similar to the reference column. Low ranked columns are columns with a selectivity different from the reference column**.
 
<font color = "blue">The column classification system also allows the comparison of two columns</font>, which are not included in the database. Characterize your two columns (preferably before use). You can enter these two sets of 4 parameter values. The first column is considered as the reference column. When the classification system classifies the columns, the F-value of the second column is also calculated and classified among the other columns in the database.

<font color = "blue">The column classification system allows the comparison of two batches of one type of column</font>. Characterize two columns from different batches (preferably before use). You can enter these two sets of 4 parameter values. The first set is considered as the reference column (reference batch). When the classification system classifies the columns, the F-value of the second column (batch 2) is also calculated and classified among the other columns in the database. If the type of stationary phase you want to examine is included in the database, you can compare your reference batch with the batch in the database as well.

The column classification system allows the follow-up of column ageing. Characterize a column before usage (new column). When this column has been used in your lab for some time ("used" column), it can be characterized again. The column classification system allows you to enter these 2 sets of 4 parameter values. The first set will be used as reference and should contain the 4 parameter values of the new column. In the second set you enter the 4 parameter values measured on the used column.

An F-value close to zero for the second column (column on top of the classification) indicates that the column properties of the two columns are similar. If you compare two batches of columns, it means that the column properties of the two batches are similar and if you follow up column ageing, it means that the properties of your used column did not change. If the column is not found on top of the classification (F is not close to zero), the two columns (or two column batches, or the used and new column) show different properties. In that case, the column classification system allows you to find columns similar to your reference column.

Conclusion: The column classification system allows the comparison of different (batches of) columns or the follow up of column ageing. F-values close to 0 (column on top of the classification) for the second column indicate column properties similar to the reference column.
____
[source](https://gbiomed.kuleuven.be/english/research/50000715/50000722/ccs/ccsmanual)
