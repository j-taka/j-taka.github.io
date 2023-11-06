---
layout: subpage
subtitle: Estimation of joint parameters from observation
permalink: /research/estimate_joint
---

This is a collaborative reseach with Dr. [Yoshihiro Sato](http://www.cvl.iis.u-tokyo.ac.jp/~yoshi/). 

We propose a vision-based technique for
recognition of a mechanical linkage. The aim is to realize
a robot system which can autonomously operate an object
with a mechanical linkage. First, using stereo vision, the
system observes the operated mechanical linkage. It recognizes
the position and posture of its parts over a sequence of
time frames using a geometric model-based approach. Next,
the system estimates the position and direction of the rotation
axis from the relative trajectory of these parts. Robustness of
the vision system with regard to occlusion is needed because
there is a great deal of overlap between the parts of the linkage,
depending on its operating state. Moreover, the rotation
axis has to be estimated from a sequence of positions and postures
in the presence of noise. We present the following two
techniques to solve these problems: 1)Occlusion robust object
tracking based on prediction. 2)Parameter estimation of the
mechanical rotation linkage from the noisy relative trajectories
of its parts. Good experimental results were achieved by
adapting these methods to some objects pairs with a linkage
mechanism.

<center>
<video controls>
  <source src="../assets/mov/lego_rgb.webm">
  <source src="../assets/mov/lego_rgb.mp4">
</video>
<p>Observation</p>	
</center>

<center>
<video controls>
  <source src="../assets/mov/lego_org.webm">
  <source src="../assets/mov/lego_org.mp4">
</video>
<p>Result of 3D Tracking</p>	
</center>

<center>
<video controls>
  <source src="../assets/mov/lego_cor.webm">
  <source src="../assets/mov/lego_cor.mp4">
</video>
<p>Removing noises using the estimated joint parameters</p>	
</center>


# Reference

1. Yoshihiro Sato, Jun Takamatsu, Hiroshi Kimura, Katsushi Ikeuchi, “Recognition of a Mechanical Linkage Based on Occlusion-Robust Object Tracking,” IEEE International Conference on Multisensor Fusion and Integration for Intelligent Systems (MFI2003) , 2003.

# Material

I would like to open the source code in near future.



