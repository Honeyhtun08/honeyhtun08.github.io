---
title: "Algorithm to Predict Stellar Masses of Satellites from Dark Matter Only Simulations"
excerpt: "An innovative algorithm that maps stellar masses to satellite halos in Dark Matter Only (DMO) simulations. It reduces computational costs while maintaining consistency with hydrodynamical simulations for luminous satellites.<br/><img src='/images/Mfinal.pdf'>"
collection: portfolio
---

## Overview

Dark Matter Only (DMO) simulations, while computationally efficient compared to Numerical Hydrodynamical (HYDRO) simulations, cannot directly compare with observational data due to the absence of baryonic processes. This project introduces a predictive algorithm to assign stellar masses to satellites in DMO simulations, bridging the gap for efficient dark matter model testing.

## Problem Statement

The relationship between halo mass and stellar mass is insufficient for nearby satellites due to environmental factors like tidal and ram pressure stripping by the host halo. To address this, the project focuses on stable properties such as 'peak' parameters rather than total halo mass.

## Methodology

1. **Comparative Analysis**: Differences between DMO and HYDRO simulations were analyzed at redshift \( z = 0 \).
2. **Parameter Selection**: Focused on stable 'peak' parameters to predict stellar masses.
3. **Algorithm Development**: Designed a map to derive stellar mass functions and radial distributions of luminous satellites.
4. **Validation**: Predictions from DMO simulations were compared against HYDRO simulations.
5. **Correction Mechanism**: Addressed overestimations for galaxies with host halo masses around \( \sim 10^{12} M_{\odot} \).

## Results

- The algorithm provides stellar mass functions and radial distributions comparable to HYDRO simulations.
- Significant cost and complexity reduction for testing dark matter models.
- Minor corrections ensured accurate predictions for bright halos in large-scale simulations.

---

### Presentation Details

This work was presented at the APS April Meeting. The paper is currently in preparation. 

[View APS Presentation Slides (PDF)](files/GFG%20Meeting%20presentation.pdf)

---

### Visual Representation

![Final Prediction of Stellar Masses](files/Mfinal.pdf)  
*Figure 1: Final Prediction of Stellar Masses from DMO simulation data.*

