# Phishing Website Detection Using Boosting

This project focuses on detecting phishing websites using boosting techniques and Feedforward Neural Networks (FNN). The method leverages features extracted from website content and metadata to differentiate between legitimate and phishing websites.

## Table of Contents

- [Introduction](#introduction)
- [Datasets](#datasets)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

Phishing websites deceive users into revealing sensitive information like usernames and passwords. This project proposes a method utilizing boosting algorithms and FNN to detect such malicious sites with high accuracy.

## Datasets

We used two publicly available datasets:

1. **Dataset 1:**
   - **Source:** [Mendeley](https://data.mendeley.com/datasets/c2gw7fy2j4/3)
   - **Instances:** 11,430
   - **Features:** 87

2. **Dataset 2:**
   - **Source:** [GitHub Dataset](https://github.com/username/repository)
   - **Instances:** 58,645
   - **Features:** 111

Both datasets include features like URL length, domain age, HTTPS presence, and HTML meta tags.

## Methodology

### Feature Extraction

- **Features:** Extracted 87 and 111 features from the datasets, including URL structure, HTML content, SSL information, and domain age.

### Boosting Algorithm

- **Algorithms Used:** AdaBoost and Feedforward Neural Networks (FNN).
- **AdaBoost:** Combined multiple weak classifiers to create a strong classifier.
- **FNN:** Evaluated for comparison due to its ability to model complex non-linear relationships.

## Results

- **Dataset 1:**
  - **AdaBoost Accuracy:** 93.91%
  - **FNN Accuracy:** 96.15%
  - **AdaBoost Precision:** 94.04%
  - **AdaBoost Recall:** 93.79%
  - **AdaBoost F1-Score:** 93.91%

- **Dataset 2:**
  - **AdaBoost Accuracy:** 89.9%
  - **FNN Accuracy:** 93.53%

FNN outperformed AdaBoost by 3.63% on Dataset 1 and achieved higher accuracy on Dataset 2.

## Conclusion

The proposed boosting-based method, especially with FNN, demonstrated superior performance in phishing website detection compared to AdaBoost and other traditional algorithms.


3. Ensure you have the necessary datasets:

    - Dataset 1: [Mendeley Dataset](https://data.mendeley.com/datasets/c2gw7fy2j4/3)
    - Dataset 2: [GitHub Dataset](https://github.com/username/repository)



