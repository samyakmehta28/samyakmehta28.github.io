---
layout: page
title: Recommender Systems Project
description: Under Professor Julian McAuley, I conducted an exploratory data analysis on the UCI Bank Marketing dataset and applied machine learning techniques such as Logistic Regression, Neural Networks, Random Forests, KNN, and XGBoost for predictive modeling.
importance: 2
category: ML & AI
img: assets/img/project_2.png
---

Please find the report for this project [here](https://drive.google.com/file/d/1Wn86lcLZUJkRDxIk1y7nk2yCSkmB23hV/view?usp=sharing).

# [Enhancing Term Deposit Subscription Recommendations in Banking through Machine Learning](https://drive.google.com/file/d/1Wn86lcLZUJkRDxIk1y7nk2yCSkmB23hV/view?usp=sharing)

### Project Overview:

In the modern banking landscape, characterized by intense competition for deposits and regulatory challenges, efficient marketing strategies are critical. This project focuses on analyzing and optimizing a marketing campaign from Banco de Portugal, aimed at increasing client subscriptions to term deposits during and after the Great Recession. The primary goal is to develop robust machine learning models to predict the likelihood of a client subscribing to a term deposit based on various features related to client demographics, economic conditions, and past interactions.

### Objectives:

- To assess the effectiveness of various machine learning models in predicting the success of marketing campaigns.
- To provide banks with data-driven recommendations for targeting potential clients more effectively.
- To improve the precision of direct marketing efforts in the banking sector, thereby increasing the conversion rates for term deposit subscriptions.

### Methods:

- Data Analysis and Preprocessing:

  - The dataset, containing 41,188 samples with 21 features, was collected from a Portuguese retail bank.
  - Features include both categorical (e.g., job, education, marital status) and numerical data (e.g., age, Euribor rate).
  - The data underwent extensive exploratory data analysis (EDA) to understand feature distributions and correlations addressing missing values and imbalances.

- Feature Engineering:

  - Critical features influencing term deposit subscription were identified through descriptive analysis and hypothesis testing.
  - Feature selection techniques were applied to enhance model performance.

- Model Development:

  - Various machine learning models, including linear regression, neural networks, support vector machines (SVM), random forests, and XGBoost, were employed to classify the likelihood of term deposit subscription.
  - Models were evaluated based on accuracy, precision, recall, and area under the curve (AUC) metrics.

- Handling Class Imbalance:
  - Given the imbalance in the dataset, techniques such as SMOTE (Synthetic Minority Over-sampling Technique) were used to enhance the model's ability to correctly classify minority class samples (clients who subscribed to term deposits).

### Key Findings:

- Performance Metrics: The best-performing model was XGBoost, achieving a significant AUC score, indicating high predictive accuracy.
- Feature Importance: Features such as age, job, education, and previous interactions with the bank emerged as significant predictors of term deposit subscriptions.

### Marketing Insights:

The analysis provided actionable insights into the profiles of clients most likely to respond positively to marketing campaigns, enabling more targeted and efficient marketing strategies.

### Conclusions:

The project successfully demonstrated the application of machine learning to enhance the marketing strategies of a banking institution. By identifying key client features and developing robust predictive models, the project highlights the potential for significant improvements in marketing efficiency and conversion rates for term deposits.

### Future Work:

- Further refinement of models with more advanced techniques and larger datasets could improve accuracy.
- Exploring additional features and external economic indicators could enhance predictive capabilities.
- Integration of the developed models into a real-time decision-making system for dynamic marketing strategies.
- This project exemplifies how data-driven approaches can revolutionize marketing efforts in the banking sector, providing a competitive edge in attracting and retaining clients for term deposit products.
