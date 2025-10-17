---
name: 'TraSGen: A Distributed, Scalable and Continuous Trajectory Stream Generator'
speakers:
  - Salman Ahmed Shaikh
  - Komal Mariam
  - Hiroyuki Kitagawa
  - Akiyoshi Matono
categories:
  - Presentation
  - Research
year: 2025
links:
  - name: Paper
    absolute_url: https://doi.org/10.1145/3764921.3770159
    icon: file
---

The widespread use of location-enabled mobile devices, such as smartphones, smartwatches, and air tags, has led to the generation of massive amounts of spatio-temporal trajectory data. This data is utilized by various commercial and government organizations for diverse applications. Benchmarking these applications is challenging, as the existing network-based trajectory generators are batch-oriented, lack scalability, and are unable to produce continuous trajectory streams. To address this, we introduce TraSGen, a distributed, scalable, and continuous trajectory stream generator. TraSGen generates realistic network-based trajectories using various traffic flow models that incorporate real-time road traffic, near-by stationary and moving objects, and other parameters. It takes a GeoJSON-based network as input, where each node and edge can include multiple properties. These properties, combined with traffic information, are used by the models to predict the next trajectory stream point. TraSGen is capable of balancing trajectory stream generation speed with accuracy to suit application needs. Built on a shared-nothing architecture, it is horizontally scalable. A comprehensive experimental study demonstrates TraSGen’s scalability.
