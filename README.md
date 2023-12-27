# Overview
This repository contains the code and resources for a project focused on music genre classification using deep learning techniques. The project aims to answer several research questions related to the performance of different deep learning models and feature extraction methods. Various music features can be extracted from music data and for different genres, certain feature extraction methods may show better performance than others.

## Dataset
The project utilizes the GTZAN dataset, a widely used collection of audio clips across various genres, making it suitable for music genre classification tasks.

## Research Questions

Research Question 1: Model Comparison with MFCC
The first research question explores creating a music genre classification model using deep learning. Various models, including Convolutional Neural Networks (CNN), Recurrent Neural Networks with Long Short-Term Memory (RNN-LSTM), and Multi-Layer Perceptron (MLP), are trained using Mel-Frequency Cepstral Coefficients (MFCC) as the extracted music features.

Research Question 2: CNN Performance with Different Features
The second research question investigates the performance of a Convolutional Neural Network (CNN) when trained using different music features, including MFCC, spectrogram, and mel spectrogram. This analysis helps understand the impact of feature selection on the model's accuracy.

Research Question 3: Deep Learning vs. Traditional Machine Learning
The third research question focuses on comparing the performance of deep learning models (CNN, RNN-LSTM, MLP) with traditional machine learning models such as logistic regression, Support Vector Machines (SVM), and k-nearest Neighbors (KNN). This comparison provides insights into the effectiveness of deep learning in music genre classification compared to classical machine learning approaches.


## Results
The CNN model trained using spectrogram shows an accuracy of 92%. The second best performing model is the RNN-LSTM model which displays an accuracy of 80% when trained using MFCC. Deep learning models display higher performance compared to machine learning approaches in this study.
