---
layout: post
title: 'The Jungle Book: management, caching and preview of many animals'
permalink: junglebook
categories:
    - anim
    - dhc
    - vfx
---

The creation of the visual effects for The Jungle Book was characterized by shots with many different animals (the largest shot had 207 creatures). These animals interacted with each other and the movements of some were related to or affected by the movements of others. Because of this, each character needed to be animated with a notion of the movement of the surrounding animals. Unfortunately, given the complexity of each character mesh and rig, it was not possible to load, visualize or animate large numbers of characters at once. At MPC, we developed a system that integrates our Rigging, Animation and Crowd pipeline and technology to enable the caching and fast previewing of animated characters in complex shots within Maya. This way artists could animate one animal, while the other animals were displayed at a reasonable playback speed. Furthermore, the system enabled artists to easily switch across different levels of detail (LOD) of the characters. We provide performance evaluation from production data for loading and playback of different amounts of characters.

### Publication

- SIGGRAPH '16: ACM SIGGRAPH 2016 Talks &#149; July 2016 &#149; Article No.: 58 &#149; Pages 1–2 &#149; https://doi.org/10.1145/2897839.2927414
