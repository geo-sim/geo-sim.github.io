---
name: 'Editable Map-Conditioned Trajectory Generation for Human Mobility Simulation'
speakers:
  - Takayuki Mizuno
  - Shouji Fujimoto
  - Mikito Hiruki
  - Atushi Ishikawa
categories:
  - Presentation
  - Research
year: 2026
---

Geospatial simulation of infrastructure interventions requires mobility generators that respond directly to edited maps, yet many data-driven generators do not expose the map as an editable condition. We formulate this task as map-conditioned autoregressive generation of human mobility: a road raster conditions a decoder that emits nominal 31.25 m mesh-cell tokens at one-minute intervals. The mesh-local vocabulary supports held-out and locally edited maps without retraining or vocabulary changes. We instantiate a ResNet-50 visual-prefix configuration and a Vision Transformer (ViT) cross-attention configuration, trained from scratch on 87,400 smartphone-derived trajectories from 874 meshes in Ishikawa Prefecture, Japan; 219 meshes are held out. We evaluate map sensitivity by comparing correct-map and within-split shuffled-map generations with held-out real trajectories. On the 110-mesh test split, for the ResNet-50 configuration, correct-map generations are closer than shuffled-map generations on 60% of meshes under Hausdorff-based energy distance (𝑝= 0.021), while DTW is directional but inconclusive (57%, 𝑝= 0.074); correlation with real density is 0.38 with the correct map versus 0.01 with shuffled maps. The ViT configuration shows weaker trajectory-level sensitivity and smaller density gains. An illustrative bridge-removal edit changes generated continuations without retraining. Together, these results support the feasibility of editable-map human-mobility simulation.
