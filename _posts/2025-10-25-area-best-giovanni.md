---
title: "Giovanni's best paper at AREA (ECAI workshop) :)"
excerpt: ""
tags:
  - AREA2025
  - multi-agent causal reinforcement learning
  - multi-agent reinforcement learning
  - structural causal models
  - multi-agent systems
  - publication
header:
  teaser: /assets/talks/discoli2025-rl-swarms-title.png
---

Dear fellow researchers, [ECAI'25 just concluded](https://ecai2025.org/), and with it also its workshops, too. 
There, [Giovanni Briglia](https://giovannibriglia.github.io/) (and we co-authors, too) had a very nice surprise: his very first **best paper award** :) Of course, we hope that's just the start for him 🚀

![image-center]({{ site.url }}{{ site.baseurl }}/assets/giovanni-ecai-best-rotated.jpeg){: .align-center}

Giovanni presented the following paper about **causal multi-agent reinforcement learning** applied to multi-robot systems (📖 [proceedings here](https://link.springer.com/chapter/10.1007/978-3-032-08049-3_4)):

![image-center]({{ site.url }}{{ site.baseurl }}/assets/2025-area-abstract.png){: .align-center}

When it comes to multi-robot systems (MRS) 🤖, Reinforcement Learning (RL) faces a few challenges, among which is the risk of performing dangerous actions and learn unsafe policies.
Hence, we augmented standard RL algorithms with **causal discovery and inference** 🔍, enabling robots to: 🚫 Avoid risky actions and 🧭 Predict outcomes more reliably :)

On purpose, we designed a modular causal augmentation pipeline that:

  - 📊 **Learns a core causal model** from robot-environment interactions
  - 🧮 Uses causal inference to filter unsafe or suboptimal actions
  - 🧠 Integrates seamlessly with popular RL algorithms like IQL, VDN, and Qmix

![image-center]({{ site.url }}{{ site.baseurl }}/assets/causal_rl_frameworks.png){: .align-center}

By testing on the 🧭 Navigation, 🐦 Flocking, and🚦 Give-Way scenarios taken from the [VMAS simulator](https://github.com/proroklab/VectorizedMultiAgentSimulator), we observed three key results: 

  - ✅ Improved safety: Fewer risky actions and collisions
  - 📉 Reduced variance in performance
  - ⚖️ Mixed outcomes depending on task complexity and algorithm cooperation level

The takeaway message is that **causal learning and reasoning** can enhance safety and performance in MRS, but that **collaborative causal discovery** is likely to unlock even better results!

Feel free to [contact me](mailto:stefano.mariani@unimore.it) for a pre-print, any inquiry, or even better **to join us** in this research :)
📂 Code & experiments: https://github.com/Giovannibriglia/CausalBenchMARL

Peace.
