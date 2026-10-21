---
name: 'GeoTrack: Projective Trajectory Mapping in Ego-Centric Geosimulation'
speakers:
  - Kaishuu Shinozaki-Conefrey
  - Ryan Kim
  - Jiayi Hao
  - Paul M. Torrens
categories:
  - Presentation
  - Research
year: 2026
---

Everyday urban environments are rich with useful information, such as waypoints, landmarks, and pedestrian trajectory patterns, that can be extracted as building blocks for real-to-synth pipelines. While enhanced sensors such as LiDAR are the standard for collecting these cues, a pipeline for extracting information from simple monocular ego videos taken at the street level could provide invaluable access to the embodied experience of moving through an urban space. To lay the foundation for collecting information from such videos, we introduce GeoTrack: an end-to-end pipeline for extracting embodiment cues such as depth, trajectory, scale, projection, and pose from frames of monocular egocentric video generated within an Immersive Geosimulation Environment (IGE). GeoTrack combines state-of-the-art tools in reconstruction and depth estimation, namely COLMAP and DA3Mono, and builds a joint reconstruction harnessing the strengths of both tools. We demonstrate the efficacy of this initial foray into monocular trajectory recovery on videos from a streetscape geosimulation spanning six trials of distinct camera-pedestrian motion patterns and pedestrian densities. We collect ground-truth values and withhold them from the reconstruction pipeline, reintroducing them to evaluate our results with metrics such as absolute trajectory error (ATE) for detected pedestrians, the raw values of which ultimately range from 0.175m to 0.382m. We analyze factors such as pedestrian visibility and their impacts on pedestrian ATE, and demonstrate the foundations for a system able to recover building blocks of embodiment from monocular video alone.

