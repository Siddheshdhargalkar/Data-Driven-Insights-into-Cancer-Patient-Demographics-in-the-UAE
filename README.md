UAE Cancer Patient Data Analysis
This initiative entails a comprehensive analysis of cancer-related patient data from the United Arab Emirates. The project encompasses data preprocessing, exploratory data analysis (EDA), and the application of both supervised and unsupervised machine learning techniques using Python.

Project Goal
The primary objective is to construct predictive and clustering models that categorize cancer patient data into actionable segments. This analysis aims to enhance clinical understanding, support diagnostic decision-making, and reveal latent trends within the healthcare datasets.

Technologies and Tools Utilized
Python Programming Language

Jupyter Notebook

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Data Preparation and Cleaning
The data preprocessing phase involved several key steps:

Importing and loading datasets

Validating data integrity

Cleaning inconsistencies

Addressing missing values

Exploratory Data Analysis (EDA)
EDA was conducted to identify significant trends, anomalies, and inter-variable relationships. The analysis included:

Yearly trends in recovery rates

Recovery rates across various cancer types

Influence of smoking habits on patient outcomes

Identification of the five most prevalent cancer types and their respective recovery statistics

Supervised Machine Learning – Predictive Modeling
A range of classification algorithms were implemented to predict cancer stages (I–IV) based on demographic (age, gender, nationality, ethnicity), lifestyle (smoking status), and medical (cancer type, comorbidities, weight, height) variables. Models employed included:

Logistic Regression (both Multinomial and Ordinal)

Random Forest Classifier

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Extreme Gradient Boosting (XGBClassifier)

The most effective models—XGBClassifier, Ordinal Logistic Regression, and Random Forest—were selected for final analysis based on their performance.

Unsupervised Machine Learning – Clustering Analysis
To uncover underlying patterns and patient subgroups that could inform personalized treatment strategies, clustering techniques were applied. Key methods included:

K-Means Clustering

Principal Component Analysis (PCA) for dimensionality reduction

Key Findings
Predictive Features:

For Random Forest: Age, weight, and height were most predictive of cancer stage.

For Ordinal Logistic Regression and XGBClassifier: Cancer type, ethnicity, and comorbidities were most influential.

Identified Clusters:

Cluster 0: Middle-aged (avg. 45), East Asian patients with lower body weight, mostly non-smokers, primarily treated via surgery.

Cluster 1: Younger (avg. 36), South Asian, heavier individuals, non-smokers, receiving immunotherapy.

Cluster 2: Elderly (avg. 74), underweight patients with a higher likelihood of smoking history.

Recommendations
Based on the analysis, the following strategic recommendations are proposed:

Develop cancer-type-specific clinical interventions.

Implement culturally aware care strategies, given the influence of ethnicity on disease progression.

Design personalized treatment plans and allocate resources based on patient clustering insights. For instance, special programs should target older, underweight, former smokers.

Initiate focused screening initiatives targeting high-risk demographics (e.g., individuals aged 65+, with low BMI and a history of smoking).