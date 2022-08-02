---
authors: edited by Lenny Lin
categories:
date: "2022-06-28"
description:
draft: false
lastmod: "2022-07-18"
series: 
tags: []
title: Dwell Time Effect in SIM
toc: true
---

  

<!--more-->

**[alcorn](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=47403&sid=01dfc6e94d6251fbd385f5a1055a58af)**

Hi all,

In Agilent gc-ms software, when i want to work in SIM mode, why should I **enter dwell time for m/z value** in each time segment? The maximum acceptable value for dwell time is 100 ms whereas my GC peak width is 5 s, is it mean that signal is recorded only for 100 ms of my GC peak? What is the exact meaning of dwell time in SIM mode?

Thanks 



**[ZeroUnderOne](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=58334&sid=f979bbadb3080c1b61fe80bdc20c2d9a)**
Maybe someone can correct me if I am wrong. The dwell time is how long the instrument hones in on a specific ion before switching to next then cycling back. Let's say you are looking at 4 different ions in one segment, the dwell time would be how long it looks at ion 1 before switching to ion 2 then 3 then 4 then back to 1. Setting a proper dwell time will give you a nice looking peak as it determines how many data points you will have over the time width of the peak. If you peak time is 5 seconds then you calculate dwell time as follows.

5s x1000 = 5000ms
5000ms /20 data points over the peak = 250 ms
250ms / 4 different ions = 62.5 ms

Your dwell time would thus be 62.5 ms for each of those ions in the segment. I chose 20 data points because that typically gives a nice and smooth peak.

Hope that helps.


**[James_Ball](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=43522&sid=f979bbadb3080c1b61fe80bdc20c2d9a)**

That is correct, the dwell is how long it pauses at each ion before looking at the next. There is also a little overhead from the switching process which adds maybe another ms per ion. I normally run about 50ms each with up to about 8 ions in a group which will still be in the 2 scans per second range similar to my full scan methods.


**[ZeroUnderOne](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=58334&sid=f979bbadb3080c1b61fe80bdc20c2d9a)**
Thanks for answering

So, dwell time has no effect on intensity of SIM signal? As I know, in quadrupole analyzer sensitivity in SIM mode is decreased by increasing the number of selected ion to determine. But it seems, by choosing the proper dwell time I don't lost sensitivity by increasing the number of ions.

Lets consider two situations:
1- I have one ion to detected in a time segment, so 100 ms dwell time means each 100 ms, one data point is recorded. 
2- I have two ions to detected in a time segment, so 100 ms dwell time for each ion means each 200 ms, one data point is recorded (so the shape of peak in this situation must be lower quality than situation 1).

As each ion detected for 100 ms, sensitivity in situation 1 & 2 seems to be the same whereas in situation 2 sensitivity must be lower because two ions are detected, is it correct?


**[James_Ball](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=43522&sid=f979bbadb3080c1b61fe80bdc20c2d9a)**
Sensitivity for each ion is relative to the dwell time for that specific ion, to some extent. If you have two ions and you dwell on one for 5ms and the other for 100ms, odds are the first ion could have lower sensitivity, if both ions have the same abundance normally.

I have a method that has over 100 compounds, which would be impossible to make enough segments to have only 5-8 masses per segment, so I have more masses and only dwell for 20-50ms. For the internal standards which I know will have high abundance in the chromatogram I dwell for as short of time as possible, sometimes as low as 10ms, where for compounds that have poor response I will dwell for longer. So I may have a segment with 10 masses that have dwell times of 10ms for an internal standard compound and 30ms for compounds that respond well and maybe a 60ms dwell on a compound that responds poorly. Then the next segment may have everything set to 100ms dwell because they are all very poor response compounds, then another with all 40ms dwell. I try to make each of my segments so that the entire set is reading at a rate of about 2 replicates per second, or a total dwell time of 500ms or less for the masses in each segment.

In the Agilent systems the dwell is set for each individual mass not per segment, so you can use that to adjust the sensitivity per mass to what you need. If you dwell to short of time you do not get good reproduceability and your peaks may look rough. If you dwell too long you can saturate the detector and also have poor quality peaks. You have to adjust each mass to achieve the quality and sensitivity you want for your specific analysis. It takes a little time to get everything where you like it, but if you watch keep the total cycle time at about 2 replicates per second you should have nice quality peaks with a normal capillary column.


**[jerole](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=7245&sid=f979bbadb3080c1b61fe80bdc20c2d9a)**
Hi alcorn,

The Agilent GC-MS instruments have a fixed integration time (the time they are accumulating counts). I don't remember the exact value, but lets assume it is 0.1 ms. The dwell time is the time it repeats that process, for example a dwell time of 10 ms means that it accumulates counts 100 times (dwell time/integration time) and then it averages the result. Therefore, the dwell time should have no influence on the sensitivity, 1ms or 100ms dwell time will result in the same counts. Higher dwell times will only improve your precision, not the sensitivity. Though, high dwell times might result in a loss of sensitivity if you measure too many ions resulting in less than 4 cycles/s and not well defined peaks, you might miss the max of the peak. My recommendation is to adjust the dwell time depending on the number of ions per segment to obtain at least 4 cycles/s.

J

**[mckrause](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=8013&sid=f979bbadb3080c1b61fe80bdc20c2d9a)**
No, Jerole, that is not correct. James is correct; in SIM mode the dwell time is the amount of time (up to a limit) that the system stays set to pass a certain mass. Counting by the EM is cumulative.

It does affect your sensitivity; unfortunately, it is not a linear function. You don't double your sensitivity by setting the dwell time to 20 ms rather than 10 ms, so you can't always predict the increase in sensitivity for a given compound.

One of the keys to good quantification in SIM mode is making sure you get enough data points across the peak, so make sure that your total dwell time for any given ion set is not so large as to only give you a handful of datapoints across your peak. I know that for us this can be an issue as we routinely see 3-4 second peaks, so we typically keep our total dwell time down around 100-200 ms.


**[chemstation](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=4389&sid=f979bbadb3080c1b61fe80bdc20c2d9a)**
Dear mckrause, Jerole is correct for AGILENT GCMSD, maybe other manufacturers do it 
as textbooks explain it to be, but Agilent does not.

This was confirmed a long time ago when I had tried to increase the linear range quantitation of a targeted analysis of a dichloro containing compound, with samples of unknown and varying concentrations.

I had created a method for quantitation, and had set a low dwell time for the M+4 isotope with the theory that concentrated samples won't saturate the EM, and a long dwell time for the M ion so as to quantitate low concentration samples.  
This did not work, as I keep getting the same ion counts. When I discussed this with a knowledgeable Agilent Technician, he confirmed what Jerole had written. That for an **Agilent** GCMSD, increasing dwell time only increases the signal to electronic noise ratio, it does not change the ion counts measured.  

Which is why Agilent instruments can run Scan and SIM in the same method, and I had to split the column eluent to different detectors to increase the range of quantitation.

regards
Alex  


**[jerole](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=7245&sid=f979bbadb3080c1b61fe80bdc20c2d9a)**  
From the MassHunter help file:

>Dwell Time
>
>Dwell time is the product of sample number and integration time. To increase signal a fixed integration time of 235 us is used for SIM data in Acquisition and the tune file set for **Integr** is ignored.

I had the same discussion with a Prof. at the local University. He ran the same standard with increasing dwell times from 1 ms up to 100 ms and he got the same response in all cases.

As I wrote in the previous note, this is the case for the Agilent instrument and most likely it will be different for instruments of other manufacturers. The meaning of dwell time and/or integration time varies depending on the manufacturer.


**[alcorn](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=47403&sid=01dfc6e94d6251fbd385f5a1055a58af)**
If it is correct that higher dwell time (so what sufficient data points are gathered) has no effect on sensitive in SIM, why sensitivity is decreased by increasing number of detected ions in SIM?  
The only thing that differs is "collecting time" (so called dwell time) of each ion, which decreases when number of ions is increased in SIM.  

Any idea?


**[James_Ball](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=43522&sid=f979bbadb3080c1b61fe80bdc20c2d9a)**

I am doing a lot of SIM methods now the Agilent GC/MS, and what I am finding is that increasing dwell really doesn't increase response, but it does increase the sampling which gives a better average when the signal is processed. A smoother average will give a smoother peak which when the peak smoothing is applied can give a larger response.

On the ABI Sciex 3200 if I increase the smoothing I actually get lower response peaks because it is throwing away some response as it smooths the peak to a better average. Every instrument does it a little differently.


**[Imh](https://www.chromforum.org/memberlist.php?mode=viewprofile&u=6923&sid=f979bbadb3080c1b61fe80bdc20c2d9a)**

The debate really comes down to whether the result of a SIM event is reported in "total ions counted" or "ions per second".

If you make a series of ten 1msec measurements and average them, you're reporting "ions per msec", but you counted exactly the same number of ions, in total, as you would have, had you merely carried out a single 10msec event. The effect of SIM dwell time on precision is exactly the same in both cases.

Under the hood, Agilent might make a series of measurements and average them, or count all the ions over x msec dwell-time and divide the result by x; it would be impossible to tell which approach they'd used, because they're mathematically identical. Only an Agilent engineer knows the truth!

It doesn't really matter whether a system reports total ions, or ions per msec, but I have a slight preference for the latter, because it makes comparison of different, related species slightly more intuitive, and the absolute calibration curves are a little more independent of dwell-time. On the other hand, someone else will quite reasonably prefer to see total ions per event, because it reveals better whether the signal is adequate, or whether the dwell times need a bit of shuffling to get better quality measurements.


**Reference**  
https://www.chromforum.org/viewtopic.php?t=27935