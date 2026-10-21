---
name: 'A When Mobility Data Gets Noisy: The Need for Simulating Realistic Noise Models'
speakers:
  - Erfan Hosseini Sereshgi
  - Lance Kennedy
  - Yueyang Liu
  - Mauryan Uppalapati
  - Carola Wenk
  - Andreas Züfle
categories:
  - Presentation
  - Research
year: 2026
---

To meet the growing demand for realistic mobility data across fields such as urban planning, epidemiology, crowd management, and anomaly detection, synthetic movement datasets have increasingly been adopted in recent years. In these domains, analytical focus often centers on staypoints, key spatial locations derived from trajectory data where an individual remains stationary. However, a critical yet frequently overlooked aspect of realistic mobility simulation is the noise inherent to GPS-enabled devices and signal transmission. To simulate this inaccuracy, researchers conventionally inject Gaussian noise into synthetic trajectories, a standard practice that is also popular in computer vision, signal processing, and machine learning. In this paper, we evaluate the validity of this approach by applying Gaussian noise to a simulated dataset, extracting staypoints using a widely adopted detection algorithm, and benchmarking the results against ground-truth. Our experiments show that, regardless of the distance parameter, Gaussian noise can be effortlessly mitigated by smoothing the noisy trajectory prior to staypoint extraction. Because simple Gaussian noise is so easily filtered out, it is unsuited for trajectory simulation, pointing to the clear need for noise models that reflect real GPS error patterns.
