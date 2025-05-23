# UAE Cancer Patient Data Analysis

This initiative entails a comprehensive analysis of cancer-related patient data from the United Arab Emirates. The project encompasses data preprocessing, exploratory data analysis (EDA), and the application of both supervised and unsupervised machine learning techniques using Python.

---

## 📌 Project Goal

The primary objective is to construct predictive and clustering models that categorize cancer patient data into actionable segments. This analysis aims to:

- Enhance clinical understanding
- Support diagnostic decision-making
- Reveal latent trends within the healthcare datasets

---

## 🛠️ Technologies and Tools Utilized

- Python Programming Language  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🧹 Data Preparation and Cleaning

The data preprocessing phase involved several key steps:

- Importing and loading datasets  
- Validating data integrity  
- Cleaning inconsistencies  
- Addressing missing values  

---

## 📊 Exploratory Data Analysis (EDA)

EDA was conducted to identify significant trends, anomalies, and inter-variable relationships. Key analyses included:

- Yearly trends in recovery rates  
- Recovery rates across various cancer types  
- Influence of smoking habits on patient outcomes  
- Identification of the five most prevalent cancer types and their respective recovery statistics  

---

## 🤖 Supervised Machine Learning – Predictive Modeling

A range of classification algorithms were implemented to predict cancer stages (I–IV) based on:

- **Demographics**: Age, gender, nationality, ethnicity  
- **Lifestyle**: Smoking status  
- **Medical history**: Cancer type, comorbidities, weight, height  

Models applied:

- Logistic Regression (Multinomial and Ordinal)  
- Random Forest Classifier  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Extreme Gradient Boosting (XGBClassifier)  

**Final Models Selected**:
- XGBClassifier  
- Ordinal Logistic Regression  
- Random Forest Classifier  

---

## 🔍 Unsupervised Machine Learning – Clustering Analysis

To uncover hidden patterns and patient subgroups, clustering techniques were applied. These models support:

- Personalized treatment strategies  
- Data segmentation based on health and demographic factors  

Techniques used:

- K-Means Clustering  
- Principal Component Analysis (PCA)  

---

## 📈 Key Findings

### 🔑 Predictive Features:

- **Random Forest**: Age, weight, and height  
- **Ordinal Logistic Regression & XGBClassifier**: Cancer type, ethnicity, comorbidities  

### 👥 Identified Clusters:

- **Cluster 0**: Middle-aged (avg. 45), East Asian, lower body weight, non-smokers, surgery-treated  
- **Cluster 1**: Younger (avg. 36), South Asian, higher weight, non-smokers, receiving immunotherapy  
- **Cluster 2**: Older (avg. 74), underweight, higher incidence of former smokers  

---

## 📢 Recommendations

- Develop cancer-type-specific clinical interventions  
- Implement culturally sensitive care strategies, particularly regarding ethnicity  
- Tailor treatment plans and resources based on identified clusters (e.g., programs for older, underweight, former smokers)  
- Launch targeted screening initiatives for high-risk groups (e.g., adults 65+, low BMI, smoking history)  

---



