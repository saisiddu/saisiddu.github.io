---
title: "Reusing Landlab ecohydrology model with bias corrected data from gridded hydrometeorology products."
excerpt: "Elevation dependent ecosystem response<br/><img src='/images/KI_paper.png' width="40%">"
collection: portfolio
---
Data Science and ecosystem modeling
=====

In this work, we:
- downloaded hydrometeorology data for the state of New Mexico using OGH, a python package.
- binned the data based on elevation and analyzed spatial statistics
- downloaded meteorology data from weather stations in the area of interest
- bias corrected the binned data from gridded data products using observations from weather stations
- applied CATGrass model implemented in Landlab, similar to [this](https://saisiddu.github.io/portfolio/Landlab_model_A_CATGraSS/), for each elevation bin

In the figure below, we show the ecosystem response at: 
(a) low elevation band;
(b) mid elevation band;
and (c) high elevation band.
Drought-tolerant shrubs dominate low elevation areas. Trees dominate
mid- and high-elevation areas as precipitation increases and temperature
decreases. Grass occupy spaces opportunistically.

<img src='/images/KI_paper.png' width="50%">

For more information, checkout [this](https://github.com/saisiddu/pub_bandaragoda_etal_ems/blob/master/reuse_ecohydrology_gridhydromet.ipynb) Jupyter notebook, and
[this](https://saisiddu.github.io/publication/2019-01-01-paper-title-number-6) publication.

*PFT - Plant Functional Type (Tree, Shrub, or Grass)