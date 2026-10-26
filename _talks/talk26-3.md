---
name: 'GeoRecSim: A Multi-Agent Testbed for Recommender System Design'
speakers:
  - Nahush Shrivatsa
  - Ekin Ugurel
  - Takahiro Yabe
categories:
  - Presentation
  - Research
year: 2026
---

Online platforms mediate urban destination choices, yet existing recommender-system simulations rarely represent the spatial costs and consequences of these decisions. We introduce GeoRecSim, an open-source, multi-agent testbed for evaluating how recommender-system design shapes mobility, venue demand, emissions, and Welfare. GeoRecSim embeds a recommender within a behaviorally grounded activity-travel model operating on OpenStreetMap networks across eight U.S. metropolitan areas. Synthetic populations combine derived home-work pairs from LODES with demographic and psychometric profiles from a stated-preference survey, while leisure opportunities are represented using point-of-interest data. Agents decide whether to make discretionary trips, choose autonomously or adopt ranked suggestions, travel along street networks, and provide feedback that updates recommendations. The platform exposes tunable weights for proximity, popularity, personalization, and live footfall, enabling matched-seed counterfactual comparisons against behavior without recommendations. Experiments in four metropolitan areas reveal consistent trade-offs between recommender system typologies. GeoRecSim enables researchers, planners, and platform designers to assess the spatial, environmental, economic, and distributional consequences of ranking policies before deployment. We have made the code open source and a live interactive demo available at https://airecsim.cusp.nyu.edu/.

