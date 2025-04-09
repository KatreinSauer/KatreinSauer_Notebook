---
layout: post
title: ORIGIN - a tool to evaluate XRD spectra
category: [ Fitting and plotting ]
tags: [ remove background from fits]
---

This post shows how to use ORIGIN.

### Removing the background from a sprectrum in ORIGIN

**1) create a workbook with x,y numbers to plot** \
File \
    &#8594; new \
    &#8594; Workbook \
    &#8594; construct

**2) plot x,y numbers** \
    &#8594; mark the 2 rows with numbers \
    &#8594; right click: plott \
    &#8594; line (for example)

**2) remove background from graph** \
    &#8594; mark graph \
    &#8594; Analysis \
    &#8594; Peaks and Baseline \
    &#8594; Peak analyser \
    &#8594; Open dialog

*Inside the windows "Peak Analyser"*: \
Substract Baseline \
      &#8594; next \
User Defined \
2nd Derivative \
Enable autofit (unclick the check mark)\
&#8594; add, modify and delete the background of the graph by using the red dots \
&#8594; next \
&#8594; finish

The results will appear in the Workbook.

### Determine peak width

**1) after plotting the spectra as line plott \
 zoom with "magnifying glass"in to peak of interest** \
 &#8594; click analysis \
 &#8594; Fitting \
 &#8594; Nonlinear curve fit  
 &#8594; open dialog

 &#8594; select function, for example "Gauss"

 &#8594; data selection \
 &#8594; click "+ input data" \
&#8594; click on the right arrow  &#8594; and then "Use X-scale range"

 &#8594; advanced \
 &#8594; change "max. number of iteration" to highest number \
  &#8594; change "tolerance" to smallest number \
   &#8594; click on the arrow "fit until converged"\
    &#8594; results will be in the table
