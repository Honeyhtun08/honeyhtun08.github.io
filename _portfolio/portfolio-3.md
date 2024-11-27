---
title: "Machine Learning Methods on Fermi-LAT images"
excerpt: "Using Clustering ML algorithms to identify spacial and temporal clusters in High Energy Sky. <br/> <img src = '/files/Fermi.png'>"
collection: portfolio
---

## Overview

Fermi-LAT gamma ray telescope covers energy range from 20MeV up until 300 GeV and provides event resolved observational data which are then stored as events described by tuples. These tuples store sky coordinates, arrival time and energy. Due to the nature of the modest resolutiosn in all sky survey and very large number of data points, we need additional techniques to identify spatial and temporal clusters from Fermi photon counts images. One of the methods is using Artificial intelligence or Machine Learning algorithms to automatically detect spatial clusters inside these images. Once we accomplish identifying such regions, we can follow up with ground based Cherenkov small patch observations. In this work, I used DBSCAN (Unsupervised Density Based Algorithm to Identify Spatial Clusters) on a FERMI - LAT image with energy above 50 GeV. Using the number of minimum photons and search radius for each cluster, the DBSCAN clusters data points affected by background noise and automatically discriminates signal from background noise based on the local density of the event. I updated the original DBSCAN code to further store coordinates of cluster center, parameters of the members of the clusters (location, arrival times, energy and total number). We varied the input parameters to get the most optimal results for the clusters and cross-checked the results with established 3FHL, 4FGL and TeV catalogs. We made a record of found sources in these catalogs as well as new cluster locations in both Galactic and Extr-Galactic. We also analyzed the spatial clusters in terms of their arrival times and found clusters with closely arriving photons.




[View Final Presentation Slides (PDF)](/files/Fermi%Summer%work.pdf)

---


![Final Prediction of Stellar Masses](/files/Fermi.png)  
*Identified Photon Clusters vs Average Energy inside the Clusters.*




