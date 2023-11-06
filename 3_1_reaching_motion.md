---
layout: subpage
subtitle: Real-time reaching motion generation for a humanoid robot
permalink: /research/humanoid_kinematics
---

Mr. Satoki Tsuichihara mainly conducts this research. 

For household humanoid robots, reaching as much workspace as possible with their hands is an important issue because the locations of target objects may range from the floor to above the robot's head. At the same time,
to adapt to the constantly-changing household environment, inverse kinematics for the whole body must be solved in real time. 

To achieve real-time motion generation for a humanoid robot, we propose a method of separating the inverse kinematics calculation into simpler problems. Using regression to estimate the torso orientation, we independently solve inverse kinematics for the lower body and both arms. Next, using the target pose of both hands as input, we calculate the orientation of the torso and determine the target position of the center of mass considering the reachability of both arms. At each control step, we calculate the joint angles of the lower body from the position of the center of mass, feet poses, and torso orientation. Finally, we calculate the joint angles of both arms. 

In experiments, we apply the proposed method to a human-size humanoid robot for reaching low-height positions while hunkering down. The proposed inverse kinematics solver is ten times faster than the numerical solution using the Jacobian matrix.

<center>
<video controls>
  <source src="../assets/mov/humanoid_kinematics.webm">
  <source src="../assets/mov/humanoid_kinematics.mp4">
</video>
</center>

# Reference
1. S. Tsuichihara, Y. Hakamata, G. A. Garcia R., J. Takamatsu, and T. Ogasawara, "Real-Time Whole-Body Motion Generation Using Torso Posture Regression and Center of Mass", ROBOMECH Journal, 5:8, pp. 1-13, 2018. 

1. Satoki Tsuichihara, Yuya Hakamata, Gustavo Alfonso Garcia Ricardez, Jun Takamatsu, and Tsukasa Ogasawara, “Accelerating Whole-body Motion Generation Using Regression of Humanoid’s Torso Posture”, In Proc. of the 16th IEEE-RAS International Conference on Humanoid Robots (Humanoids 2016), pp.16-21, 2016.

# Materials
[Slide](https://www.slideshare.net/JunTakamatsu1/kj-workshop-2016) (related to this research topic)

# Acknowledgement
This work is partially supported by JSPS KAKENHI Grant Number JP16K12502.

