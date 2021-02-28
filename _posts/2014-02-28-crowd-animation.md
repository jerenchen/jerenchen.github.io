---
layout: post
title: Multi-character Navigation & Collision Avoidance
permalink: crowdanim
category: 
    - anim
    - dhc
---

[![crowds](media/choreocrowds.gif)](https://www.youtube.com/watch?v=ec-9rofc3M0)

We present a novel method for planning navigation animations for multiple characters. Our method supports precise calculation of interactions between a group of individuals and thus provides a plausible collision avoidance behaviour for intra-group members. Comparable previous methods have considered the planning of multi-character navigation as two stages: retrieving trajectories for each individual (motion planning) and then fitting locomotion animations to the trajectories (motion synthesis). We note that to provide plausible animation at the fine-scale, the interactions between individuals when their paths interfere is critical, and thus our main contribution is to solve motion planning and motion synthesis simultaneously. To achieve this we present a motion query-based planning technique that identifies the spatio-temporal relationship between interfered paths, and incrementally optimises their close interactions towards collision-free and artefact-free. Our technique provides for more plausible collision avoidance behaviours in that it minimises anomalies such as frequent pace and course changes caused by the conventional two-stage approach.
