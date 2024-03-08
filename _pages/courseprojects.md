---
layout: archive
title: "Course Projects"
permalink: /course_projects/
author_profile: true
---


{% include base_path %}

## **Orientation Tracking**
Our project is centered around the precise tracking of object orientation using data gathered from Inertial Measurement Units (IMUs). We've devised a methodology that leverages IMU measurements to accurately determine the three-dimensional orientation of objects as they rotate. Going beyond simple orientation tracking, our approach extends to generating panoramic images of the object's surroundings. This added functionality greatly enhances spatial perception and visualization, making it particularly valuable in fields like robotics and virtual reality.

By integrating IMU data with camera images captured from the rotating object, we're able to stitch together comprehensive visual representations of the environment. This not only provides valuable insights into the object's orientation but also offers a richer understanding of its surroundings.

We've conducted extensive validation exercises, comparing our orientation tracking results against ground truth data from VICON motion capture systems. These tests ensure the reliability and accuracy of our tracking algorithm, making it suitable for a wide range of real-world applications.

<p align="center">
  <img src="../images/panorama_image_dataset_1_GT.jpg" width="300">
  <img src="../images/panorama_image_dataset_9_GT.jpg" width="300">
  <img src="../images/panorama_image_dataset_11_Optimizatition.jpg" width="300">
</p>

## **Breakout game with Reinforcement Learning ([Link](https://github.com/Amirhosein-javadi/Artificial-Intelligence-Homeworks/tree/main/HW5/Breakout_RL))**

In this project, I learned how to implement a Deep-Q-Network (DQN) and to demonstrate that I implemented and trained a DQN and ran it on an Atari game in an OpenAI-Gym environment.

In this game, you control a spaceship that shoots bullets. At each frame, you may either move up, down or stay still. Every once in a while, some meteors colored in red show up at random at the other end of the screen, and you should avoid or destroy them. If either one of these meteors hits you, you will die!

To destroy the meteors, you have to shoot them three times; each time you shoot them, their color changes until they disappear. They change color from red to orange to yellow and then are gone.

<p align="center">
  <img src="../images/Break down.png" width="300">
</p>

## **Face Detection Using HOG ([Link](https://github.com/Amirhosein-javadi/Face-Detection-Using-HOG-Computer-Vision))**
The histogram of oriented gradients **(HOG)** is a feature descriptor used in computer vision and image processing for object detection. The technique counts occurrences of gradient orientation in localized portions of an image.

In this project, I implement a Face Detection model with HOG descriptor and run this model with some images.

<p align="center">
  <img src="../images/melli-detected-faces.jpg" width="450">
</p>

## **Panorama and Video Processing ([Link](https://github.com/Amirhosein-javadi/Panorama-and-Video-Processing-Computer-Vision))**
In this project, I learned to create a panorama from 5 keyframes in a video. This video ([Link](https://drive.google.com/file/d/1uBBLlRxK5YRrL7Tn56Gqt-QkAZrCMWrB/view)) is taken from a boulevard full of moving cars and pedestrians while the cameraman is rotates horizontally. 
<p align="center">
  <img src="../images/key-frames-panorama.jpg" width="500">
</p>

In addition to this, I extracted the background and forground of each frame of this video. 
- [Background video](https://www.youtube.com/watch?v=Qnf5Q8QWu5I)
- [Foreground video](https://www.youtube.com/watch?v=N1XlOWRwfXo)

## **Perspective Transformation with Homography ([Link](https://github.com/Amirhosein-javadi/Computer-Vision-Homework/tree/main/HW1/RANSAC%20and%20Sift))**
In this project, I implemented the perspective transform with homography with RANSAC and Sift. I apply my algorithm to a pair of photos. 

<p align="center">
  <img src="../images/Homography_Img1.jpg" width="85">
  <img src="../images/Homography_Img2.jpg" width="266">
  <img src="../images/Homography_Result.jpg" width="337">
</p>

I also implemeted this algorithm from scratch, which is available in [this link](https://github.com/Amirhosein-javadi/Computer-Vision-Homework/tree/main/HW1/Homography-Implementing-from-scratch). 

## **Poisson Blending ([Link](https://github.com/Amirhosein-javadi/Image-Processing-Homework/tree/main/HW5/Poisson%20Blending))**
In this project, I implemented the Poisson Blending algorithm from scratch. I apply my algorithm to add this airplane in the sky image.

<p align="center">
  <img src="../images/Poisson Blending_source.jpg" width="300">
  <img src="../images/Poisson Blending_target.jpg" width="300">
  <img src="../images/Poisson Blending_Result.jpg" width="300">
</p>

