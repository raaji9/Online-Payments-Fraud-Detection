# Online Payment Fraud Detection using Machine Learning

## 1. Introduction
Online payments offer convenience but also pose significant risks, particularly regarding fraud. Consumers must ensure their payments reach legitimate service providers, as fraudulent transactions can compromise sensitive data and lead to reporting issues. Businesses also face challenges, such as issuing refunds for fraudulent transactions. This study proposes a model to identify fraudulent payments by analyzing key factors, including payment type and recipient identity, highlighting the necessity for increased awareness among consumers and businesses.

## 2. Related Work
The synthesis of models for identifying fraudulent transactions in online payments presents challenges due to the diverse methodologies and datasets used in various studies. Issues include data acquisition, preprocessing, selecting appropriate processing procedures, and analyzing outcomes (Kolodiziev et al., 2020). The sensitivity of actual payment data, which contains personal information, restricts access to only authorized companies (Ranjan et al., 2022).

## 3. Methodology
Data analysis is crucial for detecting fraudulent online payment transactions. Financial institutions can bolster defenses against fraud through machine learning techniques. Many organizations are investing significantly in developing these systems to assess the risk of specific transactions, helping them prevent losses and protect at-risk clients.

## 4. Design Specification
The research begins with data collection, followed by preprocessing and exploratory data analysis (EDA). This involves removing duplicate and null values, as well as uncovering hidden patterns in the data. We filter features to retain only those relevant to our analysis, while also comparing results with models trained on the full dataset. Subsequently, baseline models are trained on the training dataset after dividing the data into training and testing sets.

## 5. Implementation
This section details the implementation procedures and feature selection methods. The proposed technique is implemented in Python (v.3.7) using Google Colab as the integrated development environment (IDE). Python's extensive libraries for data handling, preprocessing, and strong community support make it an ideal choice for machine learning applications.

## 6. Evaluation
The primary goal of this research is to assess the performance of supervised machine learning techniques, including Artificial Neural Networks, and to determine if our proposed method outperforms state-of-the-art approaches. We conducted two experiments: [1] evaluating model performance with all dataset features, and [2] evaluating performance using a filtered feature set (excluding certain features). Metrics such as recall, specificity, F1-score, AUC score, and the AUC-ROC curve were selected for comparison, given the imbalance in our data. We utilized a confusion matrix for a comprehensive performance assessment, focusing on True Positives and True Negatives for accuracy evaluation (Rambola et al., 2018).

## 7. Conclusion and Future Work
Online payment fraud remains a significant issue in recent decades. This research highlights the importance of feature selection techniques in reducing false positive rates. Various machine learning algorithms, including logistic regression and Random Forest, were implemented to predict transaction fraud. While we achieved notable results, reaching a zero false positive and negative score is essential for financial organizations due to its impact on customer retention and refund costs. Future work will focus on achieving zero false positives and negatives, potentially through model combinations to enhance predictive accuracy.
