---
layout: subpage
subtitle: Safety in human-robot interaction
permalink: /research/safety_HRI
---

Dr. [Gustavo Garcia](http://robotics.naist.jp/~garcia-g/) 	mainly conducts this research. 

With the increasing physical proximity of Human-Robot Interaction (HRI), ensuring that robots
do not harm surrounding humans has become crucial. Therefore, we propose Asymmetric Velocity
Moderation as a low-level controller for robotic systems to enforce human-safe motions. While our
method prioritizes human safety, it also maintains the robot's efficiency. 

Our proposed method restricts the robot's speed according to (1) the displacement vector between human and robot, and (2) the robot's velocity vector. That is to say, both the distance and the relative direction of movement is taken into account to restrict the robot's motion. Through real-robot and simulation experiments using simple HRI scenarios and dangerous situations, we demonstrate that our method is able to maintain the robot's efficiency without undermining human safety.

<center>
<video controls>
  <source src="../assets/mov/safety_HRI.webm">
  <source src="../assets/mov/safety_HRI.mp4">
</video>
</center>

# Reference

1. Gustavo Alfonso Garcia Ricardez, Akihiko Yamaguchi, Jun Takamatsu, and Tsukasa Ogasawara, “Asymmetric Velocity Moderation for human-safe robot control,” Advanced Robotics, Vol. 29, No. 17, pp. 1111-1125, 2015.



