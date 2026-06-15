---
title: Hydrodynamical Simulations
subtitle: ChaNGa, MANGA
excerpt: Studying the formation scenarios on how TŻOs form.
date: 
author: ""
draft: true
# draft: true
# tags:
#   - hugo-site
# categories:
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

Using a moving mesh solver (MANGA) ontop of the smooth particle hydrodynamics (SPH) code, Charm N-body GrAvity solver (ChaNGa), I simulated 5 main sequences masses spanning 5 - 15 solar masses, with three different impact parameters.

{{< video src="/videos/7_1_43_hr.mp4">}}
need alt text here

This is a simulation showing the NS (denoted by the x marker) colliding with the 7 solar mass main sequence star. (The core is denoted by the pentagon.) The TŻO fully merges at around [TIME THEY MERGE] and settles into a dynamical TŻO in hydrostatic equilibrium.

### Radial Profiles


<!-- ![alt text](/img/changa/sep_dens_time_final.pdf) -->

{{< img src="/img/changa/sep_dens_time_final.pdf" alt="description" >}}

Plot from Williams et al. (2025), looking at the central density and separation betweeen the core and the NS over time.

