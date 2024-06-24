# IOT-Cybersecurity-using-Machine-Learning-for-Distributed-Denial-of-Service-DDoS-Attacks
My research experience at Universidad de Panama where I focused on a implementing Classification Algorithms like Decision Trees, Logistic Regression, Random Forest to evaluate the IOT CICDDoS2019 dataset on DDOS attacks

## Project Overview

This project explores the application of machine learning algorithms to enhance cybersecurity for Internet of Things (IoT) devices, focusing on the detection and prevention of Distributed Denial of Service (DDoS) attacks. Using the CICDDoS2019 dataset, the project implements Random Forest, Decision Tree, and Logistic Regression algorithms to classify and predict DDoS attacks.

## Problem Statement

The primary goal of this project is to evaluate the effectiveness of machine learning techniques in preventing IoT-related data breaches, specifically focusing on DDoS attacks. The study considers two main types of DDoS attacks: LDAP and NETBIOS.

## Project Structure

### 1. Data Acquisition
- **Source**: [CICDDoS2019 Dataset](https://www.unb.ca/cic/datasets/ddos-2019.html)
- **Description**: The dataset includes benign and DDoS attack traffic captured in real-world scenarios.

### 2. Data Preprocessing
- Cleaning and transforming the data
- Handling missing values
- Feature selection and extraction

### 3. Model Training and Evaluation
- **Algorithms Used**:
  - Random Forest Classifier
  - Decision Tree Classifier
  - Logistic Regression
- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

## Scripts Description

### `DDOS_data_preprocessing.ipynb`
This script handles the preprocessing of the CICDDoS2019 dataset, including:
- Loading the dataset
- Cleaning and transforming data
- Handling missing values
- Feature selection and extraction

### `DDOS_LDAP_NETBIOS_CLASSIFIER.py`
This script handles the training and evaluation of machine learning models, including:
- Splitting the dataset into training and testing sets
- Training Random Forest, Decision Tree, and Logistic Regression models
- Evaluating model performance using accuracy, precision, recall, F1-score, and confusion matrix

This script visualizes the results, including feature importance, confusion matrices, and performance metrics for each model.

## Results

- **Best Performing Model**: The Decision Tree classifier exhibited the highest accuracy for classifying DDoS attacks.
- **Key Findings**:
  - **Random Forest**:
    - Accuracy: 99.993%
    - Precision: 1.0
    - Recall: 1.0
    - F1-score: 1.0
  - **Decision Tree**:
    - Accuracy: 99.998%
    - Precision: 1.0
    - Recall: 1.0
    - F1-score: 1.0
  - **Logistic Regression**:
    - Accuracy: 88.032%
    - Precision: 0.81 (for class 0), 1.0 (for class 1)
    - Recall: 1.0
    - F1-score: 1.0

## References

1. Strecker S., Dave R., Siddiqui N., and Seliya N. (2021). A Modern Analysis of Aging Machine Learning-Based IoT Cybersecurity Methods. Journal of Computer Sciences and Applications, 9(1), pp.16-22.
2. Rashid Md., Kamruzzaman Joarder, Hassan Mohammad, Imam Tasadduq, Gordon Steven. (2020). Cyberattacks Detection in IoT-Based Smart City Applications Using Machine Learning Techniques. International Journal of Environmental Research and Public Health, 17, 9347. 10.3390/ijerph17249347.
3. Canedo Janice & Skjellum Anthony. (2016). Using machine learning to secure IoT systems. 219-222. 10.1109/PST.2016.7906930.
4. Bagaa M., Taleb T., Bernabe J., and Skarmeta A. (2020). A Machine Learning Security Framework for IoT Systems. IEEE Access, 8, pp.114066-114077.
5. Liang F., Hatcher W., Liao W., Gao W., and Yu W. (2019). Machine Learning for Security and the Internet of Things: The Good, the Bad, and the Ugly. IEEE Access, 7, pp.158126-158147.

This README file provides a structured and detailed overview of the IoT Cybersecurity project, ensuring that anyone accessing the repository can understand the project's purpose, structure, usage, and results.
