---
layout: project
type: project
image: img/openpl.png
title: "Exploratory Analysis of Powerlifting Data"
date: 2025-4-29
published: true
labels:
  - Python
  - Machine Learning
  - MediaPipe
summary: "Analyzing the OpenPowerlifting Dataset with machine learning."
---

Our paper for this project can be found <a href="../pdf/435final.pdf">here</a>.

## The Project
For ICS 435, we were tasked to use machine learning for a given task or problem. In this project, my partner and I analyzed the OpenPowerlifting dataset to see which features correlated the most with a person's age, bodyweight, and lift performance. 

## My Contribution
I mainly worked on preprocessing the data for each of the models. I split the dataset into male and female portions, filtered out NaN and invalid values, and only focused on lifters in the United States. I also dropped columns we wanted to predict. The features I was responsible for predicting were age and bodyweight. I was also responsible for examining which features correlate the most which the features predicted, and explaining why or why there is not a correlation. 

## Takeaways
This project was fun, but ended up growing very large. We used five different machine learning models to predict each feature. In addition, since the dataset was partitioned into male and female portions, we ended up with a lot of models (around 50) that we had to examine and report the parameters and performance of. We initially did not expect the project to grow as large as it did, but since we were essentially running the same models with different features, we decided to stick with exploring more feature correlations. 