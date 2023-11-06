---
layout: subpage
subtitle: A service robot based on DCNN-based generic object recognition and ontology
permalink: /research/dcnn_ontology
---

Mr. Yosuke Osaki started this research as a main conductor and implemented the baseline system. Mr. 
Mael Aubert, who is an intern from University of Paul Sabatier, expanded the system.

Semantic information (e.g., natural language) is very useful for an order to a service robot. Examples of orders are "warm a food using a microwave" and "bake a bread using a bread machine." Realizing such orders requires conversion to robot motions in 3D, that is, metric information.
For that purpose, we propose to use both powerful object recognition based on deep learning and ontology. The former helps conversion between semantic and metric information and the latter helps semantic manipulation; the order "warm a food using a microwave" is interpreted as rotating a dial and pushing a start button. 

In this research, we assume operations of unknown home appliances as target tasks. We employ Faster-RCNN and YOLO for object recognition and collect the images for training through the internet. We annotate not only home appliances but also functions (e.g., buttons, dials, and bars of doors) on the images. We construct the ontology using the SPAEQL Protocol. We actually implement the proposed system on Softbank Robotics, Pepper, and investigate the possibilities of the proposed method.

<center>
<video controls>
  <source src="../assets/mov/model_free_manip_v1.webm">
  <source src="../assets/mov/model_free_manip_v1.mp4">
</video>
<p>First version</p>	
</center>

# Reference

1. G. A. G. Ricardez and Y. Osaki and M. Ding and J. Takamatsu and T. Ogasawara: “ Estimating the Operation of Unknown Appliances for Service Robots using CNN and Ontology”, Proceedings of the Second International Conference on Robotic Computing (IRC 2018), pp. 181-182, CA, USA, 2018.

# Material

[Slide](https://www.slideshare.net/JunTakamatsu1/jk-workshop)

