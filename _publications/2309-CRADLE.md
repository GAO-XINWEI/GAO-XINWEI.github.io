---
title: "CRLLK: Constrained Reinforcement Learning for Lane Keeping in Autonomous Driving"
collection: publications
category: manuscripts
permalink: /publication/2025/02/09/2025_CRLLK
excerpt: 'We modeled the problem of lane-keeping as a constrained optimization problem and presented a constrained RL based solution to the problem. The weight coefficients are adaptively learned without scenario-specific tuning and grid search. Empirically, we observe that our approach surpasses traditional RL-based approaches.'
date: 2025-02-08
venue: AAMAS 2025, Detroit, Michigan, USA  # ''
slidesurl: # 'http://academicpages.github.io/files/slides1.pdf'
paperurl: # 'http://academicpages.github.io/files/paper1.pdf'
citation: # 'Xinwei Gao, Arambam James Singh, Gangadhar Royyuru, Michael Yuhas, and Arvind Easwaran. 2025. CRLLK: Constrained Reinforcement Learning for Lane Keeping in Autonomous Driving. In Proc. of the 24th International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2025), Detroit, Michigan, USA, May 19 – 23, 2025, IFAAMAS, 3 pages.'
---

Lane-keeping (LK) in self driving cars or autonomous driving requires to make decisions and consider multi-objective function like maximizing driving distance, minimizing lane deviations and collisions in real-time. Traditional reinforcement learning (RL) approach balance multi-objectives with hand-tuning reward functions, which requires scenario-specific tuning for the suitable weight coefficients. To address this challenge, we formulate LK as a constrained RL problem, where we use driving distance as the reward and other objectives, such as lane deviations and collisions, as cost constraints. Under this framework, the weight coefficients are also automatically learned along with the policy, eliminating the need for scenario-specific tuning. We evaluate our approach on a popular autonomous driving platform called Duckietown in both simulation and real-world settings. Empirically, our constrained approach outperforms various baselines on the Duckietown platform in terms of lane deviation safety and lane maintain reliability. Ablation studies demonstrate the insights into how constraint parameters affect trade-offs between safety and efficiency. Additionally, we have successfully transferred and validated our approach in real-world lane-keeping scenarios, which is crucial for demonstrating its practical value.
