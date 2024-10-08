# Waze User Churn Prediction

![Data Analytics](https://www.freecodecamp.org/news/content/images/2023/04/Data-Analytics-Advanced-Certifications.jpg)

# Google Advanced Data Analytics Professional Certificate Projects

This repository contains the project completed as part of the Google Advanced Data Analytics Professional Certificate program. The program focuses on developing skills in data analysis, 
data visualization, and machine learning using Google Cloud Platform (GCP) tools and services.

## Table of Contents

# Waze User Churn Prediction

![Waze Logo](https://m-cdn.phonearena.com/images/article/125729-wide-two_940/Waze-has-hidden-a-secret-Mood-emoticon-heres-how-you-can-get-it-to-appear-on-your-phone.webp?1593973810)

## Project Overview

This project focuses on predicting user churn for Waze, a popular GPS navigation software. The main goal is to build models that can accurately identify users at risk of churning by analyzing patterns in user behavior and interactions with the app. Accurate churn prediction helps companies like Waze retain users by implementing targeted retention strategies, ultimately reducing user loss and improving profitability.

The dataset for this project is sourced from Kaggle and contains various features related to user behavior, including app sessions, driving patterns, and more.

## Objectives

The objectives of this project are to:
- **Develop and evaluate multiple machine learning models** to predict churn, including Random Forest and XGBoost.
- **Apply deep learning models** such as Convolutional Neural Networks (CNN), Recurrent Neural Networks (RNN), Long Short-Term Memory networks (LSTM), and Gated Recurrent Units (GRU) for more complex patterns in the data.
- **Analyze and interpret the results** to provide actionable insights for reducing user churn.

## Dataset

The dataset consists of 13 attributes and 14,999 entries that capture user behavior and interactions with the Waze app. Key features include:
- `sessions`: Number of app sessions initiated by a user.
- `drives`: Number of driving sessions recorded by the user.
- `driven km drives`: Total distance driven by the user.
- `label`: Churn indicator (1 for churned users, 0 otherwise).
  
For more information, refer to the [dataset on Kaggle](https://www.kaggle.com/datasets/juliasuzuki/waze-dataset-to-predict-user-churn).

## Project Structure

1. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions of key features, identified outliers, and examined relationships between variables.
   - Applied univariate and bivariate analysis to understand the characteristics of the dataset.

2. **Data Preparation and Feature Engineering**
   - Cleaned the dataset by handling missing values and outliers.
   - Created new features such as `Kilometers per Drive` and `Percentage of Sessions to Favorite Destinations` to enhance model performance.
   - Applied the Synthetic Minority Over-sampling Technique (SMOTE) to address class imbalance.
   - Standardized numerical features using `StandardScaler` to improve model performance.

3. **Machine Learning Models**
   - Implemented and evaluated machine learning models like Random Forest and XGBoost.
   - Tuned hyperparameters and compared results using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.

4. **Deep Learning Models**
   - Built several deep learning models, including:
     - **CNN**: Achieved the highest overall performance with an accuracy of 74.3% and an AUC-ROC of 0.737.
     - **RNN**: Captured sequential data patterns with an accuracy of 72.85%.
     - **LSTM**: Designed to capture long-term dependencies in the data.
     - **GRU**: Showed strong recall performance with an accuracy of 73.05%.

5. **Model Evaluation**
   - Compared model performance using evaluation metrics. The CNN model emerged as the best-performing model overall, while the GRU model excelled in identifying true churners (high recall).

## Key Results

- **Best Model:** The CNN model achieved the highest overall performance, with an Accuracy of 76.47%, Precision of 70.78%, and an AUC-ROC of 0.7548.
- **GRU Model:** Achieved the highest Recall of 67.91%, making it particularly useful in scenarios where minimizing false negatives is crucial.
- **XGBoost Model:** Outperformed the other models in Precision (78.98%), Recall (78.80%), F1-Score (78.88%), and Accuracy (81.25%), demonstrating strong performance in identifying churners.
- **Random Forest:** Provided competitive results but was outperformed by XGBoost and the deep learning models.


## Conclusion

The deep learning models, particularly the CNN and GRU, demonstrated strong predictive performance for Waze user churn. The CNN model, in particular, offers a balanced approach and is well-suited for deploying churn prediction strategies. By identifying at-risk users, Waze can apply targeted interventions to retain users and improve overall customer retention. The XGBoost model also shows excellent performance, especially in Precision and Accuracy, and could be a valuable tool in the churn prediction arsenal.

## Future Work

- Fine-tune models with additional hyperparameter optimization to enhance performance.
- Explore additional deep learning models or ensemble methods to achieve better results.
- Integrate model predictions into Waze’s customer retention strategies for more effective user management.
---

Let me know if you'd like to add or adjust anything further!
