---
title: CoNi-MPC/OA
date: 2025-10-07
image:
  focal_point: 'top'

summary: 
abstract: 

authors: [Baozhe Zhang 张宝哲, Xinwei Chen 陈鑫炜]
tags: [MSR]
---

Cooperative Non-inertial Frame Based Model Predictive Control

<!--more-->

In this project, we presents a novel solution for UAV control
in cooperative multi-robot systems, which can be used in various
scenarios such as leader-following, landing on a moving base, or
specific relative motion with a target. Unlike classical methods
that tackle UAV control in the world frame, we directly control
the UAV in the target coordinate frame, without making motion
assumptions about the target. In detail, we formulate a non-linear
modelpredictivecontrollerofaUAV,referredtoastheagent,within
a non-inertial frame (i.e., the target frame). The system requires
the relative states (pose and velocity), the angular velocity and the
accelerations of the target, which can be obtained by relative local-
ization methods and ubiquitous MEMS IMU sensors, respectively.
This framework eliminates dependencies that are vital in classical
solutions, such as accurate state estimation for both the agent and
target,priorknowledgeofthetargetmotionmodel,andcontinuous
trajectoryre-planningforsomecomplextasks.Wehaveperformed
extensive simulations to investigate the control performance with
varying motion characteristics of the target. Furthermore, we con-
ductedrealrobotexperiments,employingeithersimulatedrelative
pose estimation from motion capture systems indoors or directly
from our previous relative pose estimation devices outdoors, to
validate the applicability and feasibility of the proposed approach.