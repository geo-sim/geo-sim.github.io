---
name: 'GeoLife+: Large-Scale Simulated Trajectory Datasets Calibrated to the GeoLife Dataset'
speakers:
  - Hossein Amiri
  - Richard Yang
  - Andreas Züfle
categories:
  - Presentation
  - Research
year: 2024
links:
  - name: Paper
    absolute_url: https://dl.acm.org/doi/10.1145/3681770.3698573
    icon: file
---
Analyzing individual human trajectory data helps our understanding of human mobility and finds many commercial and academic applications. There are two main approaches to accessing trajectory data for research: one involves using real-world datasets like GeoLife, while the other employs simulations to synthesize data. Real-world data provides insights from real human activities, but such data is generally sparse due to voluntary participation. Conversely, simulated data can be more comprehensive but may capture unrealistic human behavior. In this Data and Resource paper, we combine the benefit of both by leveraging the statistical features of real-world data and the comprehensiveness of simulated data. Specifically, we extract features from the real-world GeoLife dataset such as the average number of individual daily trips, average radius of gyration, and maximum and minimum trip distances. We calibrate the Pattern of Life Simulation, a realistic simulation of human mobility, to reproduce these features. Therefore, we use a genetic algorithm to calibrate the parameters of the simulation to mimic the GeoLife features. For this calibration, we simulated numerous random simulation settings, measured the similarity of generated trajectories to GeoLife, and iteratively (over many generations) combined parameter settings of trajectory datasets most similar to GeoLife. Using the calibrated simulation, we simulate large trajectory datasets that we call GeoLife+, where + denotes the Kleene Plus, indicating unlimited replication with at least one occurrence. We provide simulated GeoLife+ data with 182, 1k, and 5k over 5 years, 10k, and 50k over a year and 100k users over 6 months of simulation lifetime.
