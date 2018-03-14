---
layout: post
title:  "Depth Mirror (Fall 2017)"
tags: Arduino hardware python Kinect C 
sidebar: true
text: true
description: An array of solenids designed to act as a depth mirror. Final project for Physical Computing course. 
image: https://courses.ideate.cmu.edu/60-223/f2017/wp-content/uploads/2017/12/finished-solenoids-768x576.jpg
---
I intended to create an 2D array of solenoids that would respond to changes in depth input through a kinect. It would essentially reflect the depth in the image captured by the kinect. 

However, I found it very difficult to take input from the kinect and send this data to the arduino simultaneously, so instead I first record a history of depth data from the kinect, and then send it to the arduino via bluetooth, which it then uses to move the solenoids.

process diagram: 
![process](https://courses.ideate.cmu.edu/60-223/f2017/wp-content/uploads/2017/12/IMG_20171207_151632872-768x576.jpg)

circuit board I made for 4×4 array of 5V solenoids:
![circuit](https://courses.ideate.cmu.edu/60-223/f2017/wp-content/uploads/2017/12/16sols-768x576.jpg)

[Full decription of project](https://courses.ideate.cmu.edu/60-223/f2017/depth-mirror-final/)  
[DEMO VIDEO](https://www.youtube.com/watch?v=fpj6dSkBT7g)

