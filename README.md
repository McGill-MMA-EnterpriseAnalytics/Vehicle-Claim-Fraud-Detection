# vehicle-claim-fraud-detection

INSY 695 Enterprise Analytics - Winter 2023 - Group 5

## Vehicle Insurance Fraud Detection
Vehicle insurance fraud involves conspiring to make false or exaggerated claims involving property damage or personal injuries following an accident. Some common examples include staged accidents where fraudsters deliberately “arrange” for accidents to occur; the use of phantom passengers where people who were not even at the scene of the accident claim to have suffered grievous injury, and make false personal injury claims where personal injuries are grossly exaggerated.

## About this dataset
This dataset contains vehicle dataset - attribute, model, accident details, etc along with policy details - policy type, tenure etc. The target is to detect if a claim application is fraudulent or not - FraudFound_P

## Data Source

Original Data:[Vehicle_claim_fraud_detection](https://www.kaggle.com/datasets/shivamb/vehicle-claim-fraud-detection)

Clean Data:

[dataset after preprocessing](https://github.com/McGill-MMA-EnterpriseAnalytics/vehicle-claim-fraud-detection/blob/main/data/cleaned_data.csv)

[dataset after preprocessing & removed the imbalanced issue](https://github.com/McGill-MMA-EnterpriseAnalytics/vehicle-claim-fraud-detection/blob/main/data/Fraud_sampledtrain.csv)

## Framing the problem
- Objective: The objective is to develop a machine learning model that can accurately detect cases of fraudulent vehicle claims. The goal is to reduce the amount of money that the insurance company loses to fraudulent claims, while also reducing the time and resources spent investigating false positives.
- Use case: The solution will be used by the insurance company to automatically flag potential fraudulent claims for further investigation. The model will be integrated into the company's claims processing system and will automatically analyze each claim as it is submitted.
- Current solutions: The insurance company may currently rely on manual inspection of claims or rules-based systems to flag potential fraud. These approaches may be time-consuming and error-prone, leading to false positives or false negatives.
- Problem framing: This is a supervised learning problem, as we have labeled examples of both fraudulent and legitimate claims that can be used to train a model. The solution should be designed to work offline, as claims can be processed after they are submitted.
- Performance measurement: Performance can be measured using a combination of precision, recall, and F1 score, as well as accuracy and AUC-ROC. The specific metrics to use will depend on the specific business requirements and trade-offs between false positives and false negatives.
- Alignment with business objective: The performance measures are aligned with the business objective of reducing the amount of money lost to fraudulent claims and reducing the time and resources spent investigating false positives.
- Minimum performance: The minimum performance needed to reach the business objective will depend on the specific business requirements and trade-offs between false positives and false negatives. However, the model should be designed to minimize the number of false positives and false negatives to reduce the time and resources spent on further investigation.
- Comparable problems: There are many comparable problems in fraud detection, such as credit card fraud detection, insurance claims fraud detection, and healthcare fraud detection. Experience and tools from these related fields can be reused to help solve this problem.
- Human expertise: Human expertise may be available in the form of fraud investigators or claims specialists who can help to label training data and provide domain-specific knowledge about fraudulent claims. Their input can be valuable for improving the accuracy of the model and reducing the risk of false positives and false negatives.

## Data Exploration

## Data Preparation &Feature Engineering

## Modelling

## Causal Inference
