---
layout: subpage
subtitle: A fully automated annotation approach without any manual intervention using visual markers
permalink: /research/auto_learn
---

Mr. Takuya Kiyokawa mainly conducts this research. 

Automated factories use deep learning-based vision systems to accurately detect various products. However, training such vision systems, requires manual annotation of a significant amount of data to optimize the large number of parameters of the deep convolutional neural networks. Such manual annotation is very time-consuming and laborious. To reduce this burden, we propose a fully automated annotation approach without any manual intervention. To do this, we associate one visual marker with one object and capture them in the same image. However, if an image showing the marker is used for training, normally the neural network learns the marker as a feature of the object. We propose the method to make the neural network to ignore the marker. Experiments verified the effectiveness of the proposed method in comparison with manual annotation, both in terms of the time needed to collect training data and the resulting detection accuracy of the vision system.

<center>
<video controls>
  <source src="../assets/mov/auto_learn.webm">
  <source src="../aasets/mov/auto_learn.mp4">
</video>
</center>

# Reference
1. Takuya Kiyokawa, Keita Tomochika, Jun Takamatsu and Tsukasa Ogasawara: “Fully Automated Annotation with Noise-Masked Visual Markers for Deep-Learning-Based Object Detection,” IEEE Robotics and Automation Letters, vol. 4, no. 2, pp. 1972-1977, 2019.


