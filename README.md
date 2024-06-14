# Enhancing Disease Detection with Machine Learning

## Project Overview

This project presents a Python-based approach to identify and predict the type of virus affecting patients. The model focuses on four main diseases: COVID-19, RSV, Influenza type A, and Influenza type B. Using the Random Forest algorithm, the model demonstrates exceptional performance with a testing accuracy of 1, training accuracy of 0.9467, and cross-validation accuracy of 0.9458. Following the classification process, the model provides patients with a curated list of traditional medications and a convenient link for free communication with healthcare professionals.

## Objectives

- To alleviate the financial burden on individuals seeking medical testing and prescriptions.
- To mitigate the potential negative impact of false predictions by recommending medications carefully selected to minimize adverse effects.
- To enhance accessibility to healthcare services through an easily accessible website for disease diagnosis.

## Introduction

In the realm of healthcare, the utilization of machine learning algorithms has gained significant attention as a means to enhance disease detection and diagnosis. Disease detection refers to the process of identifying the presence and characteristics of a specific medical condition or disease in an individual. This project aims to present a novel model that employs various algorithms to detect and classify diseases, with a specific focus on RSV, influenza type A and type B, and COVID-19.

## Methodology

### Data Collection
Researchers and hospitals have provided open access to data related to COVID-19, RSV, and Influenza A and B. The COVID-19 data set was procured from Kaggle, and it contains 5434 rows and 21 columns. The dataset includes variables related to symptoms, medical history, and diagnostic test results.

### Data Preprocessing
Data preprocessing is a critical step to ensure the quality and usability of the data. The primary stages include cleaning the data, handling missing values, and selecting relevant features.

### Model Training
The Random Forest algorithm was used for training the model due to its high accuracy in handling datasets with common symptoms among different diseases. The model was trained on the collected datasets and evaluated using cross-validation techniques.

## Results

The Random Forest algorithm demonstrated exceptional performance with a testing accuracy of 1, training accuracy of 0.9467, and cross-validation accuracy of 0.9458. The model accurately classified the diseases based on the symptoms and provided insights for appropriate treatment plans.

## Conclusion

This machine learning model has the potential to revolutionize disease detection and diagnosis, leading to timely interventions and improved patient outcomes. By suggesting traditional treatments with no known side effects, the model ensures the safety and well-being of the patients.

## Future Work

Future improvements could involve expanding the dataset to include more diseases and enhancing the model's capability to handle multiple infections simultaneously. Additionally, incorporating more advanced algorithms and refining the data preprocessing steps could further improve the model's accuracy and reliability.

