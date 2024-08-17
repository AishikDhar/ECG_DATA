# **Classification of ECG data using non-linear time series analysis**

## **Overview**

This repository contains code and documentation related to my project on analyzing patient ECG (Electrocardiogram) data using advanced machine learning algorithms. The primary focus is on using Support Vector Machines (SVM) and k-Nearest Neighbors (KNN) for classification tasks and deriving insights from the data.

### **Project Goals**

ECG analysis in recent times has always played an important role as it helps in efficient diagnosis and in providing valuable information for clinical applications. This thesis will give an overview about the PTB-XL dataset being used and the results which are obtained after intensive data analysis including data collection, data preprocessing, data exploration and time series analysis, and lastly creating a model for classification of healthy and unhealthy patients.

## Method
The method to achieve our goal is to first collect and import the raw ECG signals from the PTB-XL dataset into the system. On the imported ECG signals, baseline correction is performed using a high pass filter and then we perform standardization to compute the statistical quantifiers. The signals then undergo frequency domain analysis through the Fast Fourier Transform (FFT) method to identify key spectral components from the power spectrum. This is followed by peak detection on the time series which provides with RR intervals. Machine learning algorithms are then applied which gives insights regarding the patient health.

## Results
The T test which has been performed on the ECG signals of healthy and unhealthy person shows a significant difference between the groups. The T value obtained for Mean RR interval is 4.48 and P value obtained is 7.59×10−9 also the T-statistic for standard deviation of RR intervals is -9.18and the P-value is 5.50e-20. After applying the machine learning algorithm of Random Forest classifier which gave the best accuracy of 0.70 while the Support Vector Machine gave an accuracy of 0.65.

## Conclusion
We have been able to get a detailed overview about how different machine learning algorithms classifies between healthy and unhealthy patients. As more research work and advanced neural network methods are done, may lead to better accuracy and help in clinical diagnosis of ECG

### **Key Features**

Data Preprocessing: Includes cleaning, normalization, and feature extraction from ECG signals.
Machine Learning Models: Implementations of SVM and KNN for classification tasks.
Performance Evaluation: Metrics such as accuracy, precision, recall, and F1-score.
Visualization: Plots and graphs to visualize ECG data and model performance.
