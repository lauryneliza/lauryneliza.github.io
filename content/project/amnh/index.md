---
title: Stellar Companion Astrometry
subtitle: 2021 Summer AMNH REU
excerpt: Identifying Dynamical Masses of Long Period Companions using Orbit Fitting Code with HGCA Astrometry
date: 2026-07-26
author: 
draft: true
# tags:
# - undergrad-REU
categories:
- Undergraduate Research
- Published
# layout: single
links:
 - icon: book
   icon_pack: fas
   name: Paper
   url: https://iopscience.iop.org/article/10.3847/2041-8213/ac382c
# - icon: github
#   icon_pack: fab
#   name: code
#   url: https://github.com/apreshill/bakeoff
---

### Identifying Dynamical Masses of Long Period Companions Using Orbit Fitting code with HGCA Astrometry
## Background
The Hipparcos-Gaia Catalog of Accelerations contains a subset of stars that appeared to be accelerating during a cross calibration between the High Precision PARallax Collecting Satellite (HIPPARCOS) catalog and Gaia. ([Brandt 2021](https://ui.adsabs.harvard.edu/abs/2021ApJS..254...42B/abstract))

A proposed cause of these accelerations is the presence of a previously unknown stellar companion. We aimed to constrain the masses of these companions using sophisticated orbit fitting codes. 

## orvara

Orbits from Radial Velocity, Absolute and/or Relative Astrometry (orvara) measures precise masses and other orbital parameters from the HGCA catalog ([Brandt et al. 2021](https://ui.adsabs.harvard.edu/abs/2021AJ....162..186B/abstract)). Using the NASA Keck HIRES RV curves, we focused on companions within 10 - 100 Jupiter masses within 20 parsecs and were able to fit the orbit of 15 Sge b.

## Results

{{< img src="/img/reu/amnh/15Sge_2.png" alt="a plot showing radial velocity in meters per second on the y-axis and a plot showing epoch in years on the xaxis" >}}
*Radial velocity of 15 Sge b*

{{< img src="/img/reu/amnh/15Sge_1.png" alt="" >}}
*orvara output of the astrometric orbit of 15 Sge b*