# Study on the Effect of Feature Selection and Hyperparameter Tuning on Random Forest for Phishing Website Classification  
### Studi Pengaruh Seleksi Fitur dan Hyperparameter Tuning pada Random Forest untuk Klasifikasi Web Phishing

## 📖 Project Description
This project investigates the effectiveness of feature selection and hyperparameter tuning on the **Random Forest** algorithm for detecting phishing websites. The study compares various feature selection techniques and hyperparameter optimization methods to enhance the performance of the classification model.

## 📊 Dataset
- **Source**: [UCI Machine Learning Repository - Phishing Website Dataset](https://archive.ics.uci.edu/dataset/327/phishing+websites)
- **Total Data**: 11,055 URLs
- **Number of Features**: 31 (all nominal)
- **Objective**: Classify URLs as **phishing** or **non-phishing**

## 🛠 Research Methodology
1. **Feature Selection**
   - **Chi-Square**
   - **Recursive Feature Elimination (RFE)**
2. **Hyperparameter Optimization**
   - **Bayesian Optimization**
3. **Model Evaluation**
   - **K-Fold Cross Validation**
   - **Recall Score**
4. **Model Comparison**
   - Random Forest with Bayesian Optimization on:
     - All features
     - Chi-Square Selected Features
     - RFE Selected Features

## 📊 Results and Analysis
- The model is evaluated using **K-Fold Cross Validation**, with **Recall Score** as the primary metric.
- The comparison of models based on feature selection and hyperparameter optimization is presented in the notebook.
