# Flight Delays Prediction

Accurate flight departure time prediction is crucial for the efficient utilization of airport resources and improving collaborative decision-making processes within the aviation industry. This project leverages deep learning techniques to accurately predict flight departure times.

## Table of Contents

- [Introduction](#introd89iuction)
- [Related Work and Background](#related-work-and-background)
- [Project Description](#project-description)
- [Results](#results)
- [Comparison](#comparison)
- [Conclusions](#conclusions)
- [Relevant Links](#relevant-links)

## Introduction

The aviation industry plays a pivotal role in connecting people and companies across the globe. However, flight delays present significant challenges to both passengers and the industry. This project aims to predict flight delays using a dataset from the Bureau of Transportation, helping airlines and airports make more informed decisions and reduce costs.

## Related Work and Background

Previous studies have used machine learning and deep learning algorithms to predict flight delays. However, many of these models consider a large number of variables. This project focuses on screening the key factors affecting flight delays, simplifying the modeling process, and providing accurate predictions for airport scheduling.

## Project Description

This section outlines the key steps in the project:

- Data Cleaning: The dataset is cleaned by handling missing values and removing unnecessary columns.
- Feature Selection: Relevant variables are selected to predict flight delays.
- Data Balancing: To address imbalanced data, the Synthetic Minority Over-sampling Technique (SMOTE) is applied.
- Model Architecture: An Artificial Neural Network (ANN) model with multiple dense layers and dropout is used.
- Training and Evaluation: The model is trained and evaluated using accuracy, confusion matrix, and classification metrics.

## Results

The project achieved remarkable results, with an accuracy of 99% using the ANN model. The confusion matrix and classification metrics demonstrate the model's high performance.

## Comparison

The project compares multiple models, including Softmax, models with different numbers of hidden layers, and the ANN model. The ANN model with 6 hidden layers and dropout outperforms other models.

## Conclusions

The project successfully achieved its research objectives. Feature importance was quantitatively determined, and an ANN model with an accuracy of 99% was developed for flight delay detection. Future directions could include feature selection methods and the exploration of other models such as LSTM.

## Relevant Links

1. [Research Paper](https://www.mdpi.com/2071-1050/14/22/15367)
2. [Medium Article](https://medium.com/analytics-vidhya/using-machine-learning-to-predict-flight-delays-e8a50b0bb64c)
3. [Blog Post](https://industryforever.wordpress.com/2017/10/12/predicting-flight-delays-using-tensorflow-and-machine-learning/)
