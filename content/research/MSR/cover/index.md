---
title: COVER
subtitle: Cross-Vehicle Transition Framework for Quadrotor Control in Air-Ground Cooperation

date: 2025-10-07
image:
  focal_point: 'top'

summary: Cross-Vehicle Transition Framework for Quadrotor Control in Air-Ground Cooperation

tags: [MSR]
---


<!--more-->

UAV transitions across UGVs enable diverse air-ground cooperation (AGC)
applications, such as cross-vehicle landing, delivery, and rescue. However, achieving precise and efficient transitions across multiple moving UGVs without prior
knowledge of their trajectories remains highly challenging. This paper proposes
COVER, a cross-vehicle transition framework for quadrotor control in AGC scenarios. In COVER, the UAV is directly controlled in UGVs’ body frames as
non-inertial frames, thus eliminating all dependencies in the world frame. Each
transition process is divided into three stages: the initial stage, transition stage,
and final stage, with pre-set stage transition points and stage-varying system
states. Then, an optimal reference trajectory is generated at each stage by solving
a non-linear programming (NLP) problem. The effect of the target UGV’s rotation on the initial relative velocity is eliminated to obtain a dynamically feasible
and smooth transition reference trajectory. Finally, we design a stage-adaptive
model predictive control (SAMPC) method, proposing a novel MPC position reference mode to avoid indirect routes at the transition stage. The SAMPC method
effectively mitigates the flight instability caused by reference frame transition
and eliminates the effect of reference frame rotation at the transition stage. And
it can flexibly adapt to accurate requirements at the final stage by switching
position reference mode and adjusting cost weights. Simulation benchmarks and
extensive real-world experiments validate that our approach can achieve smooth,
short-distance, and accurate cross-vehicle operations.


**Related Publications:**
- [COVER: cross-vehicle transition framework for quadrotor control in air-ground cooperation
](https://fast-fire.github.io/publication/journal-article/rqy-cover/)