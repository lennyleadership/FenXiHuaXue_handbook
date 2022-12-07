---
weight: 1
title: Pressure Problems
authors: null
categories: null
tags: ["Margine note demo", "double line demo"]
description:  
draft: false
date: "2022-11-08"
lastmod: "2022-11-08"
series: null
toc: true
---

Essentials of LC Troubleshooting, Part I: Pressure Problems  
December 1, 2021   
Dwight R. Stoll  
LCGC North America, December 2021, Volume 39, Issue 12   
Pages: 572–574  

<!--more-->
---



## Everything is Possible

In the area of pressure problems, everything is possible. Sometimes pressure is unexpectedly low, but stable. Other times the pressure is too low, and appears to steadily decrease. The same is true for pressures that are higher than expected. In other cases, the observed pressure may seem to be about right, but it is fluctuating more than usual. <b>Figure 1</b> illustrates the idea that pressure problems appear in all kinds of different ways, and lists the specific situations that are discussed in this article. The list of pressure-related problems shown in <b>Figure 1</b> is not exhaustive; in this installment, I focus on those problems that I see most frequently in practice.<a class = "sidenote">test</a>  

<figure>
  <img width = "540" src = "/docs/images/Figure 1 LC Troubleshooting.webp"/>
  <figcaption class = "bottom"><b>Figure 1</b>: Illustration of the different ways pressure problems can appear, and the specific situations that are discussed in this article.</figcaption>
</figure>


## What Is To Be Expected?

A critical step in any troubleshooting exercise — but one that I think is underappreciated — is recognizing that there is a problem to be solved. Recognizing that there is a problem usually amounts to recognizing that what is happening with the instrument is different from what is expected to happen, and our expectations are formed from theories, empirical knowledge, and experience (4).

Before getting into details about what we can expect about pressure, a few words to clarify what it is and how it is measured in LC instruments are warranted. In LC, when we say “pressure,” we are really talking about a “pressure drop” or a “pressure difference.”

These more precise terms are indicated in various equations that relate pressure drop to other variables, such as flow using the symbol Δ*P*. Most commercially available LC systems have a single pressure readout associated with the pump that reports the pressure drop between the pump and the outlet of the system (the outlet side of a detector flow cell) that, for all practical purposes, is zero, because the atmospheric pressure of about 1 bar is usually small compared to LC operating pressures. This single pressure readout quantifies the total pressure drop across the entire flow path, but does not tell us anything about the pressure drops across individual elements of the flow path (for example, filters, different pieces of connecting tubing, and the column).

### Pressure Drop Across Connecting Tubing

Most practical high-performance liquid chromatography (HPLC) is done under conditions where flow through connecting tubing in the system is laminar. Under these conditions, the pressure drops across the different pieces of tubing can be calculated with the accuracy needed for troubleshooting purposes using Poiseulle’s Law:  
$$
\begin{equation}
\tag{1}
\Delta P_{tub} = 128 \cdot \frac{\eta \cdot L_{tub} \cdot F}{\pi \cdot d_{tub}^4}
\end{equation}
$$
where &eta; is the dynamic viscosity of the mobile phase, *F* is the flow rate, and *L<sub>tub</sub>* and *d<sub>tub</sub>* are the length and diameter of the tubing, respectively. Calculating the pressure drop using equation 1 is straightforward when all of the values needed are available; however, the dependence of viscosity on mobile-phase composition and temperature is a bit complex. Fortunately, there are some freely available web-based tools that take these factors into account (for example, see reference [5], and https://www.multidlc.org/dispersion_calculator), and provide users with quick estimates of the expected pressure drops for the tubes in their systems.

### Pressure Drop Across Columns

The pressure drop across the LC column itself (assuming the column is packed with particles) can be calculated using equation 2 (or similar). Like equation 1 for open tubes, the pressure drop depends on the column length, mobile-phase viscosity, and the flow rate (through the interstitial mobile phase velocity, *u<sub>e</sub>*). Different in equation 2 are the &Phi; term that quantifies the permeability of the packed particle bed, and the particle size term, d<sub>p</sub><sup>2</sup>.

$$
\begin{equation}
\tag{2}
\Delta P_{col} = \frac{\Phi \cdot \eta \cdot u_e \cdot L_{col}}{d_p^2}
\end{equation}
$$

As with equation 1, calculating the pressure drop across the column is straightforward once all of the values for length, viscosity, and other variables are in hand, but they are not all easy to come by. Once again, there are freely available simulators that can calculate the pressure drop for conditions of interest. Two such simulators that I am familiar with are the web-based LC simulator maintained by my group (https://www.multidlc.org/hplcsim), and the spreadsheet-based simulator developed more recently by Prof. Davy Guillarme’s group (see [6]; https://ispso.unige.ch/labs/ fanal/practical_hplc_simulator:en).

### Other Elements of the Flowpath

The other elements of an LC flow path that can contribute substantially to the pressure drop measured at the pump are inline filters (and guard columns, though these can be treated like columns as above). <u class ="red">Most inline filters sold for use in analytical LC systems are designed in a way that they will not contribute more than a few bar to the total pressure drop under typical conditions</u> (that is, less than 5 mL/min). When debris begins to accumulate on the filter, the pressure drop across the filter will increase, and become highly, and sometimes non-linearly, dependent on operating conditions (for example, flow rate and mobile-phase composition). Because it is difficult to cope with this hard-to-predict behavior, in my laboratory we simply change the filter if the pressure drop across it <u class ="red">exceeds about 10 bar</u>.

### Using These Numbers in Troubleshooting Practice

Throughout the hundreds of “LC Troubleshooting” articles John Dolan wrote, he emphasized the value of “rules of thumb” in effective troubleshooting (7) <a class = "marginnote">rule of three</a>. I completely agree, and think the value of these ideas—which are informed both by theory and experience—cannot be overstated. As an example of <u class ="red">`a rule of thumb`</u> that is useful in the context of troubleshooting pressure problems, the one that we use in my group is that <mark class = "lemon">the pressure drop across all of the tubing (no column) in a “typical” LC system is about 30 bar</mark> under the following conditions (if the observed pressure is much lower or higher than that, this should trigger a thought that something is not right):

- All tubing from injector to detector is 0.005” i.d. (120 μm); total length is about 60 cm. The capillary from pump to injector is usually larger in diameter, and does not contribute much to the total pressure drop.  
- Flow rate, 1 mL/min.; Temperature, ambient; mobile phase, 100% aqueous.

## Situations Involving Pressure That Is Lower Than Expected

There are two main problems that lead to pressures that are lower than expected.

- <b><font class = "font_upper">Leaks</font></b>. There are many different ways that a leak can occur in a LC system. The most common ones I see are related to connections (for example, tubing to valve, or tubing to column). Usually, these leaks are relatively small (that is, a few microliters per minute), and can be corrected by tightening the fitting slightly. However, be careful—forcing a metal ferrule into a connection too much can deform the port (such as a column endfitting or valve port). If you feel like the connection is already very tight, then it is better throw the capillary away and start with a fresh one. I always tell my students that <mark class = "lemon">“too loose is much better than too tight.”</mark> Another way of saying this is that it is much cheaper to replace several capillaries than it is to replace a valve stator because a capillary was overtightened and deformed or stripped the threads on a valve port. Significant leaks can also occur between the pump pistons and seals. We should never be able to see liquid emerging from the pump head in the area of the piston/seal. If liquid is observed, the seals are probably leaking and should be replaced. In my experience this problem does not occur nearly as frequently as it did with pumps 20 years ago. Finally, it is possible for polyetheretherketone (PEEK) tubing to burst, even when working below the advertised pressure limit of the tubing. When this happens it usually leads to a major, obvious leak, whereas leaks with connections and pump seals tend to be more subtle.  

- <b><font class = "font_upper">A partially obstructed solvent inlet filter</font></b>. LC pumps rely on a free, steady flow of solvent from the solvent bottle to the inlet check valve to work properly. If the inlet filter on the end of the line in the solvent bottle becomes partially obstructed by particulates or bacterial growth, this can slow the flow to the point where the pump is “starved” of solvent, and unable to deliver flow to the column at the specified flow rate, leading to lower than expected pressure. If one suspects that this might be the problem, a quick check involves simply removing the inlet filter from the solvent line. If the pressure returns to normal after the filter is removed, then the filter needs to be cleaned at a minimum, and it is usually best to just replace it altogether.

## Situations Involving Pressure That Is Higher Than Expected

Most problems involving higher than expected pressure are somehow related to <u class ="red">accumulation of debris somewhere in the system</u>. The origins of this debris vary; it can come from: (1) particulate matter in the injected sample, (2) molecules that are soluble in the sample solvent but precipitate it the mobile-phase stream, (3) polymeric material shed by pump and injector seals, and so on. The specific nature of the problem that results from this debris depends strongly on how the system is configured. Determining where the obstruction is in the system can be tricky. <u class ="red">A systematic approach to finding out where the problem lies involves removing components from <u class ="red">the flow path</u> one at a time, starting from the downstream end</u>. For example, suppose we are running at 1 mL/min, and we observe a pressure at the pump of 600 bar, which is high compared to a normal operating pressure of 250 bar. With the flow off, remove the detector from the flow path. Turn the pump back on and record the pressure. If it has only decreased by 5 bar to 595 bar, then we know that the obstruction does not lie in the detector flow path. Again, with the flow off, remove the tubing between the detector and the column outlet. Turn the flow back on and record the pressure. If it has decreased another 10 bar to 585 bar, then we know that the tubing between the column outlet and the detector is not the source of the problem. Next, remove the column, turn the flow back on, and record the pressure. There should be a significant difference between the pressure recorded with and without the column connected. Suppose in this case that the pressure is still 365 bar even without the column connected, which would be abnormal in any typical analytical LC system. Next, suppose that upon removing the inline filter installed immediately upstream from the column the pressure drops to 20 bar. This would tell us that the pressure drop over the filter itself was 345 bar (far higher than expected), indicating that the filter should be thrown away and replaced. This <u class ="red">“one-piece-at-a-time” approach</u> can feel tedious when trying to get an instrument back on track, but it is the most reliable way to isolate the problem. The three most commonly encountered scenarios are:

- <b><font class = "font_upper">An obstruction in an inline filter</font></b>. In my laboratory, partially plugged filters account for 95% of our high pressure problems. Once it is clear that a filter is obstructed, one could try backflushing them, but this solution is usually short-lived. It is far better in the long run to just replace the filter.  

- <b><font class = "font_upper">An obstruction in a piece of capillary tubing</font></b>. This does not happen very often if inline filters (0.2–0.5 μm porosity) are used immediately after the sample injector. If inline filters are not used, then the capillaries of the smallest diameters and the ones furthest upstream (that is, closest to the injector) are the most likely to become blocked. Reversing the flow through an obstructed capillary will occasionally be sufficient to remove the debris, but the most reliable solution is to just replace the capillary.  

- <b><font class = "font_upper">An obstruction at the inlet of a column</font></b>. This can also be largely prevented through routine use of an inline filter upstream from the column. If an increase in pressure drop across the column is observed over time, reversing the flow through the column can flush debris out of the inlet frit, but, in my experience, the reduction in pressure is usually short-lived. It is also important to note that some column manufacturers use frits with larger porosities at the column inlet; reversing the flow is then a bit risky, because some particles could go through the frit and be lost from the column (thank you to Prof. Chuck Lucy for this reminder). The bottom line is that it is best to avoid problems like this with the column by protecting it, through routine use of inline filters and/or guard columns.

## Situations Involving Pressure That Appears To Be Fluctuating

Most modern LC pumps are based on some variation of a reciprocating dual piston design, where the pressure variation that occurs at the end of each piston stroke can be minimized, but is difficult to eliminate entirely. <u class ="red">The specification for modern pumps is that the pressure variation should not exceed about 1%</u>. If the observed variation is much larger than 1%, then it is most likely because of one of two reasons.

- <b><font class = "font_upper">Malfunctioning check valves</font></b>. A typical reciprocating dual piston pump design relies on two check valves to keep the mobile-phase flow moving in the direction of the column. When solvent is being pushed out of the pump head toward the column, the inlet check valve closes so that solvent cannot travel back toward the solvent bottle. When solvent is being drawn from the solvent bottle into the pump, an outlet check valve closes to prevent solvent from flowing backwards into the pump head. When working properly, these check valves open and close multiple times per minute. If one or both of them does not open or close properly, there will be a significant interruption in the flow to the column, which in turn manifests as a change in pressure. Determining which of the two check valves is faulty can be tricky. One approach is to first replace the inlet check valve with one that is known to be functional. If this does not solve the problem, then re-install the original inlet valve, and change out the outlet check valve with one that is known to be functional. If this does not reduce the pressure fluctuation, then the problem does not lie with the check valves.  

- <b><font class = "font_upper">Gas bubbles in the pump head</font></b>. Even a pump with properly functioning check valves can get tripped up by an air bubble. If an air becomes trapped in a pump head (for example, after the pump has accidentally run dry, because an inline degasser is not working properly, or after a prolonged period without use), it can lead to severe flow or pressure fluctuations. Purging the pump at high flow rate (with the column disconnected) is often effective for dislodging the bubble and returning to normal operation. If this does not resolve the problem, purging with the pump head with isopropanol is another approach that often works well.

## Summary

In this first installment on essential topics in LC troubleshooting, I have discussed situations where the observed system pressure is somehow different from what is expected or normal. Effective troubleshooting for this type of problem begins with a sense for what the expected system behavior is, so that a deviation from those expectations is noticeable. While there a many different potential causes of pressure related problems (too low, too high, or fluctuation), most problems can be connected to five or six specific causes. Understanding this short list of likely causes provides a good place to start troubleshooting, but does not capture all possibilities. Readers interested in learning about a deeper list of causes and solutions are referred to the “LCGC Troubleshooting” wallchart (3).

## References

(1) D. Runser, *LC Magazine* **1**(1), 10–16 (1983).

(2) T. Kempen and D.R. Stoll, *LCGC North Am.* **39**(10), 471–475 (2021).

(3) https://www.chromatographyonline.com/view/troubleshooting-wallchart

(4) D.R. Stoll, *LCGC North Am*. **38**(10), 544–547 (2020).

(5) D.R. Stoll and K. Broeckhoven, *LCGC North Am.* **39**(6), 252–257 (2021).

(6) D. Guillarme, B. Bobaly, and J.-L. Veuthey, *LCGC North Am*. **39**(3), 144–145 (2021).

(7) J. Dolan, *LCGC North Am*. **32**(8), 546–551 (2014).

**Dwight R. Stoll** is the editor of “LC Troubleshooting.” Stoll is a professor and the co-chair of chemistry at Gustavus Adolphus College in St. Peter, Minnesota. His primary research focus is on the development of 2D-LC for both targeted and untargeted analyses. He has authored or coauthored more than 75 peer-reviewed publications and four book chapters in separation science and more than 100 conference presentations. He is also a member of *LCGC*’s editorial advisory board. Direct correspondence to: [LCGCedit@mmhgroup.com](mailto:LCGCedit@mmhgroup.com)


## Source
<a href = "https://www.chromatographyonline.com/view/essentials-of-lc-troubleshooting-part-i-pressure-problems" target="_blank" rel="noopener noreferrer">Essentials of LC Troubleshooting, Part I: Pressure Problems</a>



