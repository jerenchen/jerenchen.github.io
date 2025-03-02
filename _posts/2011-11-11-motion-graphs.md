---
layout: post
title: Environment-aware Motion Graphs
permalink: motiongraphs
categories: 
    - anim
---

[![mographs](media/mographs.gif)](https://www.youtube.com/watch?v=ptmnKLcC1MI)

The creation of plausible human animation remains a perennial problem in computer graphics. To construct long animations it is common to stitch together a sequence of motions from a motion database. Typically, this is done in two stages: planning a route and then sampling motions from the database to follow that route. We introduce an environment-aware motion sampling technique that combines the planning and sampling stages. Our observation is that in the traditional approach the route generated in the first stage over-constrains the motion sampling so that it is relatively implausible that a human would follow this animation. We combine the motion sampling and planning and show that we can find shorter and more plausible animations.

### Publication

- Je-Ren Chen and Anthony Steed. 2011. Planning Plausible Human Animation with Environment-aware Motion Sampling. In Proceedings of the Fourth international conference on Motion in games (MIG’11), Jan M. Allbeck and Petros Faloutsos (Eds.). Springer-Verlag, Berlin, Heidelberg, 51-62.

### Motion Dataset

The motion capture data used in the experiments in this research is obtained from the [CMU Motion Capture Database](http://mocap.cs.cmu.edu/). They are re-sampled to 30 frames-per-second. Here is the complete list:

| Subject_Trial | Frames | Motion Description |
| ----- | --- | --------------- |
| 16_11 | 134 | Walk, veer left |
| 16_12 | 111 | Walk, veer left |
| 16_13 | 111 | Walk, veer right |
| 16_14 | 119 | Walk, veer right |
| 16_18 | 130 | Walk, 90-degree left turn |
| 16_19 | 103 | Walk, 90-degree right turn |
| 16_31 | 106 | Walk (from stop) |
| 16_34 | 87  | Slow walk, stop |
| 16_47 | 104 | Walk (in a straight line) |
| 16_58 | 86  | Walk (in a straight line) |
| Total | 1091|                           |

### Support

- [UCL Graduate Research Scholarship](https://www.ucl.ac.uk/scholarships/graduate-research-scholarships)
- [UCL Overseas Research Scholarship](https://www.ucl.ac.uk/scholarships/overseas-research-scholarships)
- [Rabin Ezra Scholarship Fund](http://rabinezrascholarship.org)
