# 📊 Multivariate Logistic Regression - Telecom Churn Analysis 📉

## 🌟 Project Overview

Welcome to the Telecom Churn Analysis project! 🚀 This project uses multivariate logistic regression to predict customer churn for a telecom firm. Our goal is to build a predictive model to determine whether a customer will switch to another service provider based on various attributes. 📞💡

### 📋 Problem Statement

You have data from a telecom firm containing customer attributes, including:

- **Demographics**: Age, gender, etc. 👤
- **Services Availed**: Internet packs purchased, special offers taken, etc. 📈
- **Expenses**: Monthly recharge amounts, etc. 💳

Our task is to build a model to predict **customer churn**—whether a customer will leave (churn) or stay (not churn). The target variable is **'Churn'**:

- **1**: Customer has churned 🔄
- **0**: Customer has not churned 🛑

### 📂 Project Files

This repository includes the following files:

- **CSV Files**:
  - `Telecom_Churn_Data_Dictionary.csv` 📜: Descriptions of the data attributes.
  - `internet_data.csv` 🌐: Data on internet services availed by customers.
  - `customer_dataa.csv` 👥: Demographic and personal information of customers.
  - `churn_data.csv` 🔍: Target variable indicating customer churn.

- **Jupyter Notebook**:
  - `jupyter_notebook_analysis.ipynb` 🧑‍💻: Contains code for data analysis, model building, feature scaling, and evaluation.

### 🎯 Objectives

- **Data Preparation**: Load and preprocess data from CSV files. 🛠️
- **Feature Engineering**: Create features for predicting customer churn. 🔧
- **Model Building**: Train a multivariate logistic regression model. 📈
- **Evaluation**: Assess model performance using accuracy, precision, recall, sensitivity, and specificity. 📊

### 🔄 Steps Taken

1. **Data Loading**:
   - Loaded data from CSV files into pandas DataFrames. 📥
   - Explored and cleaned the data. 🧹

2. **Feature Engineering**:
   - Handled missing values and categorical variables. 🗃️
   - Scaled numerical features. ⚙️

3. **Model Building**:
   - Built a multivariate logistic regression model using the processed data. 🏗️
   - Trained the model to predict customer churn. 📊

4. **Model Evaluation**:
   - Evaluated the model using metrics like accuracy, precision, recall, sensitivity, and specificity. 🧪
   - Fine-tuned parameters to improve model performance. ⚙️

## 📋 Dependencies

- **Python 3.x** 🐍
- **pandas** 📊
- **numpy** 🔢
- **scikit-learn** 🔍
- **matplotlib** 📈
- **seaborn** 🌈
- **jupyter** 🧑‍💻

## 📈 Results

The notebook will provide you with the following outputs:

- **Performance metrics of the logistic regression model**. 🧪
- **Visualizations and insights about customer churn**. 📊

## 🤝 Contributing

Feel free to contribute to this project by submitting pull requests or opening issues for any improvements or bugs. 🛠️

## 📝 License

This project is licensed under the MIT License.  📜

## 📧 Contact

For any questions or feedback, please reach out to [my email](mailto:akashanandani.56@gmail.com). ✉️
