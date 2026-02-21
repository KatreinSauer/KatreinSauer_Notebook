---
layout: post
title: Adult Stony Corals
category: [ XRD, XRF, Raman ]
tags: [ Stylophora Pistillata and Pocillopora Verrucosa ]
---

This post is about Synchrotron based XRD, XRF, Raman data on Stylophora Pistillata

## Adult stony coral samples:
## Mature nubbins and new growth fronts


### samples
Samples can be found partially: \
CBP_Lab_Data(\\tal-nas)(Z:)/**Coral1**/Maayan

Bold samples were used in the manuscript

**SP - Stylophora Pistillata:**
- **SP3: ROI 1**
- **SP3: ROI 2**
- SPS3a (lateral)

**PP - Pocillopora Verrucosa:**
- **pp2: ROI 2**
- **pp3: ROI 2**
- pp1: ROI 1
- pp1: ROI 2
- pp2: ROI 1
- pp2: ROI 3
- pp3: ROI 1
- pp5: ROI 1
- pp5: ROI 2
- pp5: ROI 3
- pp7: ROI 1
- pp7: ROI 2

### Underwater pictures ###
 Hagai Nativ: https://www. hagainativ.com


1. Photography of corals Stillophora Pistillata \
2. SEM image

## X-ray Absorption Images ###
3. Transmission images from Spec-files (BESSY, found wihtin one of the last columns)
4. Transmission (T) transformed into Absorption (A):\
  A = 1-T \
  --> T was determined with Fiji, looking for the highest intensity value within histogram and this is defined then as "100% transmission = 1 in formula":\
a)  100% = 593751.44 \
As -A = T - 1 and T = our image:\
with Fiji:\
&#859
4; click on transmission image
&#8594; process
&#8594; math
&#8594; substract 593751.44
&#8594; afterwards multiply with (-1)


### XRD ###
In order to check if aragonite crystal intensity will change with directions all possible peaks of the spectrum will be plotted into 2D aragonite images. The following peaks are used:

| peak| channel       |  peak maximum | background   |     
|:---:|:-------------:|:-------------:|:------------:|
|(111)|  315-385 (70) |  348          | 450-500 (50) |
|(021)|  385-445 (60) |  417          | 450-500 (50) |
|(012)|  800-840 (40) |  820          | 850-900 (50) |
|(200)|  999-1045 (46)| 1022          | 850-900 (50) |
|(112)| 1120-1160 (40)| 1140          |1220-1270 (50)|
|(022)| 1158-1213 (55)| 1182          |1220-1270 (50)|
|(211)| 1338-1382 (44)| 1360          |1220-1270 (50)|
|(122)| 1450-1495 (45)| 1475          |1510-1560 (50)|
|(221)| 1630-1695 (65)| 1667          |1510-1560 (50)|
|(041)| 1800-1860 (60)| 1830          |1730-1780 (50)|
|(132)| 1910-1980 (70)| 1949          |2000-2030 (30)|




### RAMAN paper figure ###
 ## Compare with ORIGIN:  peak width of peak with the highest intensity (number 1086). The peak width broadens the more the crystals (aragonite/calcite) lose the cristalinity and apear amorphous. I want to see if ACC is preesnt ##

  &#8594; plot RAMAN sprectrum \
  &#8594; background reduction \
   &#8594; within a range of 1000 - 2000 [1\cm] peak width was determined with the Voigt-function
