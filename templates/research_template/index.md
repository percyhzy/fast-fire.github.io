---
title: CREPES-Summarized name for the research
# subtitle shown when the page is clicked.
subtitle:  subtitle shown when the page is clicked.
date: 2020-12-02
# Image pixel resolution should be around 2000*1000, 2:1 size.
image:
  focal_point: 'top'
summary: One sentense around 10 words, shown in the collection page.
# tag choices include: AutoNav, MSR, NovelRobot. Only these three will be visiable. 
tags: [AutoNav]

---

<!--more details in Markdown-->

More details when click the link.

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

**Related Publications:**

- [ColAG: A collaborative air-ground framework for perception-limited ugvs’ navigation
  ](https://fast-fire.github.io/publication/conference-paper/colag/)
- [Cost-Effective Swarm Navigation System via Close Cooperation](https://fast-fire.github.io/publication/journal-article/cost-effective/)