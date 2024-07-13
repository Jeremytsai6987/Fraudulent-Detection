# Enhancing Credit Card Fraud Detection through Machine Learning and Deep Learning

## Project Overview
This project aims to enhance the detection of credit card fraud using advanced machine learning (ML) and deep learning (DL) techniques. By utilizing real-life credit card transaction data, we apply a variety of ML and DL models to develop a robust fraud detection system. This project is a part of the MPCS 2024 Spring 53120 Applied Data Analysis course.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Installation](#installation)
- [Usage](#usage)
- [Models Implemented](#models-implemented)
- [Performance Metrics](#performance-metrics)
- [Results](#results)
- [Challenges](#challenges)
- [Future Work](#future-work)
- [References](#references)

## Data Source
The data used in this project is sourced from Kaggle and consists of real-life credit card transactions labeled as fraudulent or non-fraudulent. The dataset can be accessed using the following link:
[Link to the Data](https://www.kaggle.com/datasets/chitwanmanchanda/fraudulent-transactions-data)


## Models Implemented
The following models were implemented and evaluated in this project:
- Convolutional Neural Network (CNN)
- Autoencoder
- K-Nearest Neighbors (KNN)
- Random Forest
- XGBoost
- Logistic Regression
- Linear Regression
- Lasso Regression

## Performance Metrics
The performance of the models was evaluated using the following metrics:
- **Accuracy:** The ratio of correctly predicted observations to the total observations.
- **Matthews Correlation Coefficient (MCC):** A balanced measure that takes into account the true and false positives and negatives and is suitable for imbalanced datasets.

## Results
- **XGBoost:** Achieved the highest accuracy (0.9997) and MCC (0.91007).
- **Random Forest:** Performed well with an accuracy of 0.9996 and MCC of 0.835.
- **CNN and Autoencoder:** Did not perform as well due to the lack of spatial features in the tabular data.
- **Ensemble Learning:** While promising, it did not outperform the standalone XGBoost model.

## Challenges
- **Computational limitations:** Addressed using GPU-accelerated algorithms.
- **Overfitting:** Managed by implementing regularization techniques such as dropout.
- **Data structure differences:** Important to consider the structural differences in the data used when model performance did not meet expectations.

## Future Work
Future work includes:
- Integrating ensemble learning techniques to improve detection accuracy.
- Conducting Principal Component Analysis (PCA) to further refine the models.
- Exploring advanced deep learning architectures and real-time data streams for dynamic fraud detection.

## References
1. Awoyemi, John O., Adetunmbi, Adebayo O., & Oluwadare. (2017). Credit card fraud detection using machine learning techniques: A comparative analysis. International Conference on Computing Networking and Informatics.
2. Johan Perols. (2011). Financial Statement Fraud Detection: An Analysis of Statistical and Machine Learning Algorithms. American Accounting Association.
3. Pradheepan Raghavan and Neamat El Gayar. (2019). Fraud Detection using Machine Learning and Deep Learning. International Conference on Computational Intelligence and Knowledge Economy.

## Contact
For any questions or feedback, please contact Ya Wei Tsai at jeremyyawei@uchicago.edu
