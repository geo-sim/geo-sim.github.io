---
name: 'PhobosBC: A Blockchain-based Crowdsourced Post-disaster Mapping System and its Agent-based Simulation'
speakers:
  - Raunak Sarbajna
  - Christoph F Eick
  - Aron Laszka
categories:
  - Presentation
  - Research
year: 2023
links:
  - name: Paper
    absolute_url: https://dl.acm.org/doi/10.1145/3615891.3628016
    icon: file
---
After a major natural disaster strikes a region, emergency response often lacks information about the post-disaster state of the road network. Conflicting information about the region from multiple sources creates confusion. Thus, it is imperative to obtain an updated map, which provides accurate information about currently navigable paths and identifies hazardous locations. However, due to possible damage to communication and computation infrastructure, existing centralized geospatial services may provide outdated information. One possible solution to this problem is using Internet-of-Things based devices that are deployable without relying on a centralized service, which will be able to both acquire and disseminate local data. In this paper, we introduce PhobosBC, a decentralized system which is able to provide a reliable mapping service using volunteer work, while relying on a blockchain backend. This solution utilizes the availability of modern smartphones with GPS receivers and processing capabilities to collect sequences of GPS locations and combine them into trajectories. These trajectory data are submitted as entries into a blockchain after processing them through a smart contract. PhobosBC relies on the inherent robustness and distributed nature of blockchains to make collating and assembling a map from these paths more accurate and less susceptible to disruption. Compared to a centralized system, PhobosBC is more resilient and is able to respond to individual agents going offline while still retaining consensus. As a performance incentive, we rank volunteers by the amount of correct data submitted and publicly recognize top performers. We develop an agent-based model to simulate PhobosBC under a hypothetical disaster scenario, and we compare our approach with a crowdsourcing system which deploys a simulated central control mechanism. We share the problems faced during creation of the agent-based model and the lessons we learned. Our results show that PhobosBC is able to recreate the ground truth faster while being more fault tolerant. 
