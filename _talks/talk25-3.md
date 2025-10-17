---
name: 'STAAR-FM: Scalable Terrain-Aware Adaptive Resolution Framework for Flow Modeling'
speakers:
  - Deven Biehler
  - Tashi Stirewalt
  - Zayn Abou-Harb
  - Assefaw H. Gebremedhin
categories:
  - Presentation
  - Research
year: 2025
links:
  - name: Paper
    absolute_url: https://doi.org/10.1145/3764921.3770149
    icon: file
---

The increase in high-resolution gridded data from satellite constellations to LiDAR imagery has heightened the tradeoff between computational cost and spatial accuracy in large-scale flow analysis. Traditional single-resolution methods often result in prohibitive runtimes at fine scales or a loss of detail at coarse scales. We introduce the Scalable Terrain-Aware Adaptive Resolution Framework for Flow Modeling (STAAR-FM), a terrain-aware framework that dynamically adjusts grid resolutions based on local complexity. This approach achieves accuracy comparable to that of high-resolution models while maintaining the efficiency of coarse-resolution methods. The first module, the Attention Resolution Map (ARM), analyzes terrain characteristics in the Digital Elevation Model (DEM) to create a spatial resolution map that indicates where high detail is required. The second module, the Adaptive Resolution Kernel (ARK), enhances the D8 flow direction algorithm by utilizing a novel adaptive kernel based on the guidance of the resolution map. STAAR-FM consistently outperforms a baseline D8 flow direction method in accuracy over diverse landscapes. The framework demonstrates the usefulness of roughness as a terrain complexity heuristic to guide computational resources and highlights the advantages of dynamic resolution maps for efficient modeling of diverse topography.

