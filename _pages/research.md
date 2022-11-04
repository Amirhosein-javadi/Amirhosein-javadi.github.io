---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
# **Current Projects**

### **Nash in CycleGAN**
In a paper named [GANs May Have No Nash Equilibria](https://arxiv.org/pdf/2002.09124.pdf), it is shown that WGAN-WC, WGAN-GP, and SNGAN may have no nash equilibrium. It means that after training the Generator and Discriminator for some iterations, the pair (G_final, D_final) does not represent a Nash equilibrium. It means that by fixing the trained discriminator and optimizing the generator, the generator will change. In my research project, I showed that Nash equilibrium is viable in the [CycleGAN](https://arxiv.org/pdf/1703.10593.pdf) paradigm theoretically and by simulations. 

### **Depth Estimation in Surgical Rooms**
In this project, I am trying to create a depth estimation in surgical room with 6 cameras. My final goal is to predict depth accurately and create a 3d model of our room. Some of my current network results are shown below. (From Left to Right: Input Image, Ground Truth, Predicted Inverse Depth)

<p align="center">
  <img src="../images/Depth/0_image.jpg" width="100">
  <img src="../images/Depth/0_inv_depth.jpg" width="100">
  <img src="../images/Depth/0_prediction.jpg" width="100">
</p>
<p align="center">
  <img src="../images/Depth/1_image.jpg" width="100">
  <img src="../images/Depth/1_inv_depth.jpg" width="100">
  <img src="../images/Depth/1_prediction.jpg" width="100">
</p>
<p align="center">
  <img src="../images/Depth/2_image.jpg" width="100">
  <img src="../images/Depth/2_inv_depth.jpg" width="100">
  <img src="../images/Depth/2_prediction.jpg" width="100">
</p>
<p align="center">
  <img src="../images/Depth/3_image.jpg" width="100">
  <img src="../images/Depth/3_inv_depth.jpg" width="100">
  <img src="../images/Depth/3_prediction.jpg" width="100">
 </p>
 
### **Liver Tumor Segmentation**
In this project, I am working on a neural network for liver tumor segmentation over LiTS17 datasets. My ultimate goal is to have +95% dice score. Some of my current network results are shown below. (From Left to Right: Input Image, Ground Truth, Model Output) 

<p align="center">
  <img src="../images/Lits/0_image.jpg" width="100">
  <img src="../images/Lits/0_label.jpg" width="100">
  <img src="../images/Lits/0_output_model.jpg" width="100">
</p>
<p align="center">
  <img src="../images/Lits/1_image.jpg" width="100">
  <img src="../images/Lits/1_label.jpg" width="100">
  <img src="../images/Lits/1_output_model.jpg" width="100">
</p>
<p align="center">
  <img src="../images/Lits/2_image.jpg" width="100">
  <img src="../images/Lits/2_label.jpg" width="100">
  <img src="../images/Lits/2_output_model.jpg" width="100">
</p>
<p align="center">
  <img src="../images/Lits/3_image.jpg" width="100">
  <img src="../images/Lits/3_label.jpg" width="100">
  <img src="../images/Lits/3_output_model.jpg" width="100">
</p>

# **Previous Projects**
### **SEFDM Communication**
