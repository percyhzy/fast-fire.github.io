---
title: ColAG
subtitle: Collaborative Air-Ground System to Boost Air-Gound Cooperation

date: 2025-10-06

image:
  focal_point: 'top'

summary: Collaborative Air-Ground System to Boost Air-Gound Cooperation

tags: [MSR]
---
<!--more-->

Perception is necessary for autonomous navigation
in an unknown area crowded with obstacles. It’s challenging
for a robot to navigate safely without any sensors that can
sense the environment, resulting in a blind robot, and becomes
more difficult when comes to a group of robots. However, it
could be costly to equip all robots with expensive perception
or SLAM systems. In this paper, we propose a novel system
named ColAG, to solve the problem of autonomous navigation
for a group of blind UGVs by introducing cooperation with one
UAV, which is the only robot that has full perception capabilities
in the group. The UAV uses SLAM for its odometry and
mapping while sharing this information with UGVs via limited
relative pose estimation. The UGVs plan their trajectories in
the received map and predict possible failures caused by the
uncertainty of its wheel odometry and unknown risky areas.
The UAV dynamically schedules waypoints to prevent UGVs
from collisions, formulated as a Vehicle Routing Problem with
Time Windows to optimize the UAV’s trajectories and minimize
time when UGVs have to wait to guarantee safety. We validate
our system through extensive simulation with up to 7 UGVs
and real-world experiments with 3 UGVs.

Following this work, we further propose a system
has only one depth camera with a field of view for environmental perception. We fully explore the cooperation between robots
by proposing a Sequential Exploration and Aiding Localization
(SEAL) planning strategy for the UAV and a Collision-Adaptive
Trajectory (CAT) optimization for UGVs. The UAV assists UGVs’
localization with relative pose estimation and own global localiza-
tion, meanwhile, it focuses on exploration to provide UGVs with
abundantenvironmentalinformation.TheUGVteamcannavigate
safely and autonomously in obstacle-rich environments and even
maintain formations with only the wheel odometer and UAV’s
assistance using CAT optimization. Our method is validated both
in simulations and real-world experiments indoors and outdoors.

**Related Publications:**
- [ColAG: A collaborative air-ground framework for perception-limited ugvs’ navigation](https://fast-fire.github.io/publication/conference-paper/colag/)
- [Cost-Effective Swarm Navigation System via Close Cooperation](https://fast-fire.github.io/publication/journal-article/cnh-cost-effective/)
