---
weight: 9
authors: Carl Sims, edited by Lenny Lin
categories: 
date: "2022-01-03"
description: Advances in Liquid Chromatography Degassing - A next-generation technology brings HPLC degassing under control
draft: false
lastmod: "2022-01-03"
series: 
tags: [Sensitivity, Resolution]
title: Flat Film Degasser
toc: true
---



<!--more-->

## The Background of Degassing  

Reducing the amount of dissolved air in the HPLC mobile phase has a significant impact on the stability of system flow rate and mobile phase composition. Low pressure mixing HPLC pumps rely on only solvent entering the pump, any outgassing which occurs during transfer from the proportioning valve in to the inlet check valve can cause several types of errors. First, composition errors will occur because the volume in the transfer line contains air, not fluid mobile phase. As a bubble in the transfer line stretches, the accuracy of the mixture continues to be degraded. Finally, a bubble entering the pump can interfere with the inlet check valve such that the pump does not deliver a complete volume of mobile phase to the column, instead pushing a portion back toward the proportioning valve. Additionally, the pump must compress any bubble to the system pressure before delivery of the mobile phase to the column can occur.  

In high pressure mixing HPLC systems, dissolved gas can affect the operation of the inlet check valve forming microbubbles due to cavitation. As with low pressure mixing HPLC pumps, a bubble will cause incorrect flow which interferes with retention time. <mark>This fluctuating flow may also increase system noise in the detector depending on the detector type and sensitivity to flow</mark>. Thus, dissolved air affects the accuracy and resolution of separations, and the ability to reliably identify compounds that have been separated on the column. As a result, it has long been the case that essentially all HPLC systems include some form of degassing ranging from bulk degassing with vacuum, helium sparging, ultrasonication to the inline methods using membrane technologies including PTFE membranes and Teflon™ AF.  

Today’s HPLC systems have one of two mobile phase mixing arrangements - either the solvents are mixed before they enter the pump (low-pressure mixing); or alternatively, mobile phase mixing occurs after the pump but before the injection valve (high-pressure mixing). In both cases, efficient in-line vacuum degassing of the mobile phase mixture and its components helps to avoid chromatographic issues.  

In 1975, Tokunaga published the data set that has formed the foundation for degassing for HPLC solvent mixtures [1]. He determined the Ostwald coefficients for the solubility of oxygen in various alcohol-water mixtures and demonstrated the degree to which mixtures needed to be degassed to prevent bubble formation. This seminal paper has underpinned the development of the tubing-based degassing systems in routine use in most labs today.  


<br>
<figure>
  <img width = "540" src = "/docs/images/Screenshot 2022-01-14 101303.png"/>
  <figcaption><b>Figure 1</b>: Air Solubility in Various Water and Menthanol Mixtures</figcaption>
</figure>



Note: Adapted from Tokunaga, J Chem & Eng Data Vol 20 No 1 1975 with percentage of remaining air in both solvents shown.  

Figure 1 plots Tokunaga’s data, recalculated in the way HPLC systems mix mobile phases as volumetric percentages. The difference between the upper solid red line and the Ostwald coefficient data lines represents the supersaturation of the mixtures with dissolved air. Three example lines where the amount of air is reduced by degassing are also shown.  

From this data, the actual concentration of air in a mixture that will not outgas at atmospheric conditions is 38%, and this is the target that the majority of degassers are designed to meet (at the flow rate and applied vacuum specific to the particular instrument design requirements).  

## Challenging current practice

In-line degassers in common use today utilise tubular Teflon™ AF or polytetrafluoroethylene (PTFE) membranes. They allow air to pass through the membrane and out of the mobile phase in accordance with Henry’s Law, Dalton’s Law and Raoult’s Law. Operating at a constant vacuum level, they remove air from a mobile phase more efficiently at low flow rate and less so at higher flow. This is due to residency time within the tubing.  

It is also possible for solvent molecules to move from the mobile phase to the vacuum side of the membrane. Known as pervaporation, this effect can significantly change the concentration of the mobile phase under certain circumstances, and with certain HPLC methodologies. This is because when the vacuum is fixed at a pressure below the vapour pressure of the solvent, the pump will continue to remove both the dissolved air and solvent vapours. So long as the pump is active, the solvent supply bottle replenishes the system and solvent vapour is pumped into the atmosphere. It is therefore desirable to control pervaporation using the vacuum side of the degasser, setting as high a pressure as possible without reaching the point at which outgassing will occur in the HPLC system.  

This impacts pump and inlet check valve efficiency and can lead to inaccuracies in both mobile phase composition and pumping system flow rate potentially causing method failure because of quantification & identification issues.  

## Next-generation degassing technology

The desirable design features of any new approach to degassing should include:  
  • Lower flow restriction than tubing-based degassers  
  • Small form factor with no internal tubing fittings to leak  
  • Lowest vacuum volume to limit initial pervaporation of volatiles  
  • Constant flow restriction regardless of applied vacuum  
  • Degassing the mobile phase at the highest pressure possible without allowing the mobile phase to become supersaturated with air. Referred here as ‘high pressure degassing’, this technique reduces or eliminates solvent vapour discharge into the laboratory atmosphere.  
  • Degasser integrated into HPLC system control software to enable intelligent control of vacuum to ensure improved degassing efficiency.  

In addition, a degasser that could be universally applied  
- at flow rate ranges as great as 10 mL/min, depending on style of HPLC system   
- and with all common solvents including hexafluoroisopropanol, would be a significant advantage.  

There is now a patented flat film membrane, together with a dedicated vacuum pump control algorithm (patent pending), which addresses these goals. Figure 2 shows a schematic of the new flat membrane degasser. It is a simple design that is straightforward to implement into both low pressure and high pressure mixing HPLC systems (Figure 3). The design results in a product with minimal fittings and connections. Its highly efficient membrane has been specified with sufficient surface area to degas solvents for analytical scale HPLC systems (up to 10 mL/min flow rate). The unique flow channel layout delivers a low fluid resistance before the inlet check valve of the pump.  

<br>
<figure>
  <img width = "540" src = "/docs/images/Screenshot 2022-01-14 101705.png"/>
  <figcaption><b>Figure 2</b>: Unique patented flow channel design. Thin liquid film flows over degassing membrane</figcaption>
</figure>


<br>
<figure>
  <img width = "540" src = "/docs/images/Screenshot 2022-01-14 101835.png"/>
  <figcaption><b>Figure 3</b>: New degasser integrated into generic low- (left) and high- (right) pressure HPLC systems</figcaption>
</figure>


The companion vacuum control algorithm provides the integration into the separation method control protocol and allows selection of a given degassing efficiency for any HPLC system. Vacuum pressure can be dialled up or down to reach the exact HPLC method specification needed. A simplified interface accepts the flow rate and desired efficiency of degassing for the individual separation method from the HPLC and adjusts the vacuum to the highest pressure possible for efficient degassing. This method prevents dissolved atmospheric supersaturation while suppressing pervaporation and mobile phase concentration changes. The flow restriction is constant, regardless of the applied vacuum.

## In practice

The initial evaluation of the new degasser/control algorithm has generated some encouraging data, and positive reports on usability.
In order to characterise the degasser, a mathematical model of performance vs. applied vacuum level is derived from running HPLC separations and is stored either in the degasser controller or the HPLC control system. The first step, using the methanol-oxygen charge transfer complex at either 210 nanometers (nm) or 215 nm, is to determine the efficiency of the chamber at different flow rates and applied vacuums.  

Figure 4 illustrates efficiency vs. flow rate at four different vacuum pressures. Note that the maximum flow rate at which 30% residual air (70% efficiency) at 50 mmHg is approximately 2.5 mL/min. This is sufficient to degas a gradient or any isocratic mobile phase up to 5 mL/min, and because an efficiency of 62% (38% residual air, Figure 1) is required to prevent outgassing, an HPLC system equipped with this degasser, operated at 50 mmHg, could be expected to use method flow rates up to 7 mL/min without exhibiting bubble formation.  


<br>
<figure>
  <img width = "360" src = "/docs/images/Screenshot 2022-01-14 102342.png"/>
  <figcaption><b>Figure 4</b>: Characterisation curves showing efficiency vs flow rate of the film degasser at four different vacuum levels.</figcaption>
</figure>


Subsequent steps plot efficiency vs. vacuum levels for each flow rate and solve the efficiency-vacuum curve equations using the desired efficiency and flow rate. The formula of each curve links flow rate to output vacuum level such that once a degassing chamber is characterised, the vacuum level applied to the degasser is a function of the desired efficiency and the flow rate of the method. Degassing performance can then be tuned using vacuum control to cover the entire performance range of an HPLC system. Target degassing efficiency can therefore be constantly assured at any flow rate with minimum concentration changes, or pervaporation, in the mobile phase.

Figure 5 shows data from an experiment to compare the degassing efficiency of flat film vs. tubing-based systems. It is important to note that the vacuum levels are dramatically different but that the performance of the new film degasser matches that of the tube degasser at the desired flow rate (1 mL/min) and efficiency (70%).  

<br>
<figure>
  <img width = "360" src = "/docs/images/Screenshot 2022-01-14 102704.png"/>
  <figcaption><b>Figure </b>: Comparing a predicted vacuum level efficiency of 70% at 1 mL/min against a standard 18-inch tube degasser at 50 mmHg vacuum.</figcaption>
</figure>


This demonstrates that any degasser can be characterised, and the resulting sets of data can then be used to control the vacuum degassing system from the inputs of efficiency and method flow rate.

## Looking ahead

In summary, the development of the flat film degasser and its companion control algorithm described here provides chromatographers with an improved degassing performance when compared to degassing at constant vacuum. The benefits will not only result in improved degassing efficiency, but most importantly, in method reproducibility, lab proficiency and productivity.
For further information, visit <a href = "https://www.idex-hs.com/store/fluidics/degassers/film-degasser.html" target="_blank" rel="noopener noreferrer">IDEX: Film Degasser</a>


## References

1. Tokanuga J (1975) solubilities of oxygen, nitrogen and carbon dioxide in aqueous alcohol solutions, J Chem Eng Data, 20(1): 41-46

## About the author

Carl Sims is a Principal Scientist working for IDEX Health & Science in Rohnert Park, CA, focusing on HPLC systems in the field of membrane degassing, fluidic optics and UPLC valves. With 47 years of chemistry experience in the instrumentation field he has been awarded 52 US patents along with an additional 150 foreign equivalents focused on HPLC, Ion Chromatography, Teflon AF Optics and very early in his career, DNA synthesis. Carl is a Navy veteran and has a BS in chemistry from Fort Lewis College in Durango Colorado and a Masters Degree in Chemistry from Northern Arizona University in Flagstaff, AZ.  
