---
layout: post
title: Black corals
category: [ Indentation ]
tags: [ antpathes, sticopathes, chitin, mechnical testing ]
---

This post shows black coral (Antipathes and Sticopathes) data measured on MySpot at BESSY.

## BESSY XRD data from October/November 2020

These data show only the black corals. Within the same measurement are also Stylophora pistillata datasets included. We want here to look into and find chitin (Poli paper)

We have two branches of black coral species:

1. Antipathes
2. Sticopathes

We have the following raw datasets as h5 files measured at BESSY (MuSpot):

- 2020-10-21_set05_corundum_left_right
- 2020-10-21_set07_align_BC_long_SPS3_AlO3
- 2020-10-22_set09_BC_150um_single_Sticho_longi_100x33
- 2020-10-22_set09a_BC_150um_single_Sticho_longi_100x22
- 2020-10-22_set10_corundum_left_right_4x4
- 2020-10-22_set13_BCB3_align
- 2020-10-22_set14_BCB3_slice_1
- 2020-10-22_set14a_BCB3_slice_1
- 2020-10-22_set15_BCB3_slice_2
- 2020-10-23_set18_Sticho_Xsec_64x60
- 2020-10-23_set19_Anti_Xsec_16x18
- 2020-10-23_set19a_Anti_Xsec_16x18
- 2020-10-23_set23_Corundum_sets17to22_L_R_lineScan
- 2020-10-24_set28a_corundum
- 2020-10-24_set33_align_Sticho_dry_BC
- 2020-10-24_set34_Sticho_LR_2Angles_DRY
- 2020-10-24_set35_Sticho_MedRes_19Angles_DRY_128x19
- 2020-10-25_set36_Sticho_RadDamageAngle0_DRY_128x10
- 2020-10-25_set48_corundum_left_right_4x4
- 2020-10-27_set52_align_DRY_Anti_Branched
- 2020-10-27_set53_Anti_DRY_16x16x13
- 2020-10-27_set53a_Anti_DRY_16x16x13
- 2020-10-27_set54_align_diffTomo_Anti_WET_40x5x13
- 2020-10-27_set56_align_diffTomo_Sticho_WET
- 2020-10-27_set57_diffRot_Sticho_WET_SinglePoint360
- 2020-10-27_set58_diffTomo_Sticho_WET_3D_128x9x5
- 2020-10-28_set59_Sticho_wet10h_dry_360deg
- 2020-10-28_set63_Sticho_longitudinal_slice_4_160_um_128_344

From all these BESSY datasets I transformed set18, set19a and set23, set9a and set53a from h5 into tiff.   

# 1) Sticopathes

For Sample 2020-10-23_set18_Sticho_Xsec_64x60, here are no debye rings in this entire dataset. In the following image numbers there appears some background rings:

- 205-208
- 261
- 268-270
- 281

#
Sample 2020-10-22_set09a_BC_150um_single_Sticho_longi_100x22 looks promising. The following are the # of Debye rings (tiff) looking into with Fiji:

- 47
- 66
- 161-186 (here are the chitin peaks!!!)
- 489-... super weak
- 560-566 (good peaks)
- 658-670 (peaks without chitin close to the beamstop, but strong debye rings)
- 1055-1064 (only debye rings)
- 1133-1134
- 1139
- 1167-1169
- 1234
- 1560 - 1571

The following image is #564:

![2020-10-22_set09a_BC_150um_single_Sticho_longi_100x22_000001_no564]({{site.baseurl}}/images/2020-10-22_set09a_BC_150um_single_Sticho_longi_100x22_000001_no564.png)

The following image is #666:

![2020-10-22_set09a_BC_150um_single_Sticho_longi_100x22_000001_no666]({{site.baseurl}}/images/2020-10-22_set09a_BC_150um_single_Sticho_longi_100x22_000001_no666.png)

# 2) Antipahtes


For Sample 2020-10-23_set19a_Anti_Xsec_16x18, here are no debye rings in this entire dataset. In the following image numbers there appears some background rings:

- 110
- 126
- 183

#

Sample 2020-10-27_set53a_Anti_DRY_16x16x13 has 8 different sets of measurement which have to be separated in order to transfer them from h5 into tiff. Although there are Debye rings all over the show, the intensity is weak and Debye rings need to be summed up. This is a dry Sticopathes sample, the former sample was not prepared like that. The best immage from this dataset I could get is the follwing (#XXX):

- 1st line: 8-22
- 2nd line: 8-23
- 3rd line: 9-24
- 4th line: 9-24
- 5th line: 9-24
- ...
- 8th line: 10 - 13 are the strongest peaks of all

The following image is a single image, smothed (with Fiji), line 4, image number 23

![2020-10-27_set53a_Anti_DRY_16x16x13_000004_data_000023_00002_line4_no23]({{site.baseurl}}/images/2020-10-27_set53a_Anti_DRY_16x16x13_000004_data_000023_00002_line4_no23.png)

The following image is a MEDIAN over 4 images, smoothed (with Fiji), line 8, image numbers 10-13

![2020-10-27_set53a_Anti_DRY_MED_line8_no10_to_no13]({{site.baseurl}}/images/2020-10-27_set53a_Anti_DRY_MED_line8_no10_to_no13.png)





next steps:
 Intensity over q - spectrum
 - calibration of the spectra
 - integration of the spectra
 - plotting
 - addressing peaks
