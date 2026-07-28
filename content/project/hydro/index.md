---
title: Hydrodynamical Simulations
subtitle: ChaNGa, MANGA
excerpt: Modeling Main Sequence-Neutron Star Mergers
# date: 
# author: ""
draft: true
# draft: true
# tags:
#   - hugo-site
categories:
- Graduate Research
- Published
# layout: single
links:
 - icon: book
   icon_pack: fas
   name: Paper
   url: https://iopscience.iop.org/article/10.3847/1538-4357/ae100d
# - icon: github
#   icon_pack: fab
#   name: code
#   url: https://github.com/apreshill/bakeoff
---


---

## Simulating TŻO Formation 

A TŻO can be formed when a newly formed neutron star (NS) gets "kicked" into its companion star, which we call the "impact scenario". 

Using a moving mesh solver (MANGA) on top of the smooth particle hydrodynamics (SPH) code, Charm N-body GrAvity solver (ChaNGa), we simulated 5 main sequences (MS) masses spanning 5 - 15 solar masses, with three different impact parameters.

{{< video src="/videos/7_1_43_hr.mp4">}}

This is a simulation showing the NS (denoted by the x marker) colliding with a 7 solar mass main sequence star. (The core is denoted by the pentagon.) The TŻO fully merges at around 3 days and settles into a dynamical TŻO in hydrostatic equilibrium.

### Radial Profiles


<!-- ![alt text](/img/changa/sep_dens_time_final.pdf) -->

{{< img src="/img/changa/sep_dens_time_final.pdf" alt="a plot with 3 rows and 2 columns showing the separation over time and the central density over time of the TZOs modeled. There are 5 lines for each subplot, each corresponding to one periastron distance. " link="/img/changa/sep_dens_time_final.pdf" >}}

Separation between the center of the MS star and the NS over simulation time is plotted in the left column, with central density of our dTŻOs plotted in the right column. Each line is colored by the progenitor mass, ranging from 5 to 15 solar masses, and each row corresponds to a different type of encounter (periastron distance): direct collision, envelope disturbance, grazing encounter (Williams et al. 2025)

