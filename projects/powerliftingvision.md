---
layout: project
type: project
image: img/good-pose-1.jpeg
title: "Powerlifting Vision"
date: 2024-12-18
published: true
labels:
  - Python
  - Machine Learning
  - MediaPipe
summary: "An attempt at developing a machine learning tool to judge squat depth in powerlifting competitions."
---

Our paper for this project can be found <a href="../pdf/plvision.pdf">here</a>.

## The Project
The project my team chose to undertake for ICS 483 was to create a computer vision pipeline to judge squat depth in a powerlifting competition setting. In the sport of powerlifting, one of the lifts performed is the barbell back squat. We wanted to see if any open-source computer vision pose-estimation models would be able to accurately track the position of the lifter in order to determine if the squat was deep enough to powerlifting standards. The pipeline was essentially first annotating squat videos, then feeding them to Google's MediaPipe to obtain a pose estimation, then feeding the pose estimation to a script that would compare the knee and hip joint to make a depth decision, and also feeding the pose estimation to a multi-layer perceptron for training and making a decision. 

## My Contribution
I took on the role of being team leader for this project. I delegated tasks to my other two group members and myself. I was mainly responsible for collecting all of the squat videos and annotating them as to whether the squat in the video was depth or not. I organized all of the videos and data for our group to use in the later steps of the project.I would also assist my groupmates whenever they would need help, and kept the group on track to hit deadlines. 

## Takeaways
This project was fun, but very tedious at the same time. Watching and annotating 200+ squat videos took a lot of time, and very small dataset made it hard for our machine learning pipelines to perform well. The camera quality in the videos are also sub par. However, this is a good foundation for future work with machine learning and powerlifting. 