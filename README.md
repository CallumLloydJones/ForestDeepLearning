# ForestDeepLearning
## Table of contents

- [Introduction](#introduction)
- [Objectives](#objectives)
- [Data Science Methodology](#data-science-methodology)
    - [Project Description](#project-description)
    - [Data Science Methods](#data-science-methods)
- [Conclusions](#conclusions)
- [Status and Details](#status-and-details)
- [Technology](#technology)

## Introduction
A CSV file ('cover_data.csv') that contains 581012 observations. Each observation has 55 columns (54 features and the last one being the class).
Images are collected from Codecademy while taking their deep learning course.

### Objectives
Build a deep learning model to predict the Forest Cover type of a patient from 52 different features and ~52,000 observations.

## Data Science Methodology

### Project Description
A CSV file ('cover_data.csv') that contains 581012 observations. Each observation has 55 columns (54 features and the last one being the class).
There are no separate test datasets. So, one must hold out a small percentage of the given input as test data.
There is no information about the use of predictions. 

### Data Science Methods
- Data Preprocessing
- Data Visualisation
- Deep Learning
- Convolutional Neural Networks
  
## Conclusions
The numbers along the diagonal of the heatmap show how many were correctly classified. All other numbers on either side of the diagonal show misclassifications. 
We see that Lodgepole Pine, Cottonwood Willow, Aspen, and Douglas-Fir suffer from a high percentage of mis-classifications. We see that Lodgepole Pine is commonly mistaken for Aspen.
Further work could be done to investigate the possible causes.

Overall the accuracy of the model is ~89%.


## Status and Details
- **Project Status**: [Completed]
- **Date Coded**: 24/08/23
- **Link to Raw Dataset**: 
- **Notes**: This project was to gain a better understanding of building neural networks after taking the Codecademy course in deep learning.

## Technology
- **Language**: Python 3.11.4
- **Libraries**: pandas, numpy, matplotlib, seaborn, scipy, sklearn, tensorsflow (keras)
