---
layout: subpage
subtitle: Hardware-level reusability
permalink: /research/hardware_level_reusability
---

Robot developers develop various types of robots to satisfy users' various demands. Users' demands are altered by their backgrounds and robots suitable for users may vary.  If a certain developer offers a robot that is different from the usual to a user, the robot-specific software has to be changed. Contrarily, robot-software developers would like to reuse their developed software as much as possible to reduce their efforts. 
We propose the system design considering reusability when changing a robot. To derive the design, we reconsider the body role division and the learning-from-observation framework. The body role division is an inverse-kinematics solver designed based on human nature and can be applied to robots of various shapes. The learning-from-observation framework can represent a target task sequence in robot-agnostic representation, and thus the represented task-sequence description can be shared with various robots. To realize robot execution, we implement the skill library, robot motion primitives (brains), only considering a robot hand and we regard a robot as just a carrier to move the hand on the target trajectory. In this paper, we evaluate the reusability by using three different robots and four manipulation task sequences. The three robots can execute the same task sequences using the same human demonstrations. If we use the same hand, the software can be reused by only changing the IK solver. If we use a different hand, the software can be reused by only changing the grasp brains.

# Reference
1. Jun Takamatsu, Kazuhiro Sasabuchi, Naoki Wake, Atsushi Kanehira, and Katsushi Ikeuchi, “Learning-from-Observation System Considering Hardware-Level Reusability,” arXiv: 2212.09242 ([pdf](https://arxiv.org/abs/2212.09242)).




