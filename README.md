# Breast Cancer Classification Model Deployment

## Overview
This repository contains the code and resources for deploying a machine learning model for breast cancer classification using Azure Machine Learning. The model is trained on the Wisconsin Diagnostic Breast Cancer (WDBC) dataset to classify tumors as malignant or benign with high accuracy.

## Methodology
The deployment process involves the following steps:

### Data Ingestion
- Creation of a pipeline for data ingestion using prebuilt components.
- Uploading the WDBC dataset containing information on 569 samples and 30 different input features.

### Model Design and Training
- Designing a decision tree model using Azure ML Studio.
- Performing feature selection and splitting the dataset into training and testing sets.
- Training the decision tree model and evaluating its performance using metrics such as accuracy, precision, recall, F1-score, and AUC.

### Compute Resources
- Creation of Azure ML Compute Clusters for model training.
- Establishment of AKS Compute for model deployment to ensure efficient computing resources.

### Model Deployment
- Deployment of the trained model as a Web Service in Azure ML Studio.
- Testing the deployed model using real-time endpoint testing.
- Integration of the model into different applications using REST API endpoints in languages like C#, R, and Python.

## Dependencies
- Azure Machine Learning
- Azure ML Compute Clusters
- AKS Compute
- Python (for model development and testing)

## Dataset
You can download the Wisconsin Diagnostic Breast Cancer (WDBC) dataset from [here](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic).

## Conclusion
The deployment of the breast cancer classification model demonstrates the effectiveness of using cloud-based machine learning services for developing and deploying predictive models. By leveraging Azure Machine Learning and compute resources, we can streamline the model development and deployment process, making it scalable and efficient.
