---
layout: subpage
subtitle: A mobile robot under Dynamic Crowded Environment
permalink: /research/rt_scan_matching
---

Mr. Yusuke Hieida mainly conducts this research. 

For an autonomous mobile robot in everyday life, it is a key issue to understand the environment that changes as the time passes. Simultaneous localization and mapping (SLAM) under dynamic crowded environment is one of the solutions. 

We propose real-time scan-matching based on L<sub>0</sub>-norm minimization under dynamic crowded environment. The prior scan-matching methods are based on L<sub>2</sub>-norm minimization, because the measurement noise follows the normal distribution in static environments. This assumption is unfortunately broken in dynamic crowded environments.

We propose to use the idea of Locality Sensitive Hashing (LSH) to accelerate the L<sub>0</sub>-norm minimization, which usually is a time-consuming process. The LSH customized for our issue reduces the calculation time even in the worst cases. 

The experimental results demonstrate the effectiveness of the proposed method compared with standard L<sub>2</sub>-norm minimization and its robust version with M-estimator.

<center>
<video controls>
  <source src="../assets/mov/L0Norm.webm">
  <source src="../assets/mov/L0Norm.mp4">
</video>
</center>

# Reference

1. Y. Hieida, T. Suenaga, K. Takemura, J. Takamatsu and T. Ogasawara: “Real-time Scan-Matching Using L0-norm Minimization Under Dynamic Crowded Environment”, 4th IROS Workshop on Planning, Perception and Navigation for Intelligent Vehicles  2012.




