---
title: "Vegetation organization in a semiarid ecosystem in central New Mexico"
excerpt: "Vegetation organization on a flat watershed<br/><img src='/images/CATGraSS_Hobley_et_al.PNG'>"
collection: portfolio
---

Semiarid and desert ecosystems are characterized by patchy and dynamic 
vegetation. We implemented the Cellular Automaton Tree Grass 
Simulator CATGraSS [[Zhou et al., 2013]](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/wrcr.20259), an ecohydrologic 
cellular automaton model, in Landlab. The model couples local 
vegetation dynamics (that simulate biomass production based on 
local soil moisture and evapotranspiration) and plant establishment 
and mortality based on competition for resources and space. This model is 
driven by elevation dependent rainfall pulses and solar radiation. 
An example of CATGraSS model application in Landlab is presented in the 
figure below: 
(a) CATGraSS model flow chart showing flow between different model components; 
(b) time series of modeled grass, shrub, and tree cover fractions for CATGraSS 
implementation on a flat domain for central New Mexico climatology. 
Spatial distributions of plants in model initial condition (c), 
after 1,000 years (d), and year 1,500.  Model shows epochs of shrub 
and grass dominance in the modeled domain, while trees were outcompeted.

<img src='/images/CATGraSS_Hobley_et_al.PNG'>

This figure is from [Hobley et al. 2017](https://saisiddu.github.io/publication/2017-01-01-Landlab-3).

*PFT - Plant Functional Type (Tree, Shrub, or Grass)