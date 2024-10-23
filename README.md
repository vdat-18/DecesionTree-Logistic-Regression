# 📊 Customer Churn Prediction Project

## 🌟 Overview
This repository contains a comprehensive analysis of customer churn using various datasets in XML, JSON formats and Jupyter notebooks. The objective is to analyze customer data, develop predictive models, and identify key factors contributing to customer churn.
## 📂 Files Included

| File Name                       | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| **Customer_Churn_01.xml**        | XML dataset containing customer details and churn information.               |
| **Customer_Churn_02.json**       | JSON dataset with customer demographics and financial behavior data.         |
| **Cau2_Customer_Churn1.ipynb**   | Jupyter notebook implementing exploratory data analysis (EDA) and model 1.   |
| **Cau2_Customer_Churn2.ipynb**   | Jupyter notebook implementing data preprocessing and predictive models.      |

## 🔧 Requirements

To run the code in this project, you will need the following libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## 🧹 Data Preprocessing
We first preprocess the data to ensure it is ready for analysis. This includes:
- Handling missing values.
- Encoding categorical variables.
- Standardizing numerical features.
- Merging data from XML and JSON sources.
## 📊 Exploratory Data Analysis (EDA)
In the Cau2_Customer_Churn1.ipynb notebook, we explore key insights from the data:
- Distribution of customer churn based on demographics (age, gender, tenure).
- Analyzing customer financial behavior such as monthly charges and total charges.
- Visualizing correlations between features using heatmaps.
## 🧠 Machine Learning Models
The Cau2_Customer_Churn2.ipynb notebook focuses on developing predictive models to identify customers likely to churn. Models implemented:
- Logistic Regression.
- Decision Tree.
## 🚀 How to Run
Clone the repository:
```bash
git clone https://github.com/yourusername/Customer-Churn-Prediction.git
```
Navigate to the project folder:
```bash
cd Customer-Churn-Prediction
```
Open the Jupyter notebooks and run the cells:
```bash
jupyter notebook Cau2_Customer_Churn1.ipynb
jupyter notebook Cau2_Customer_Churn2.ipynb
```
Make sure the XML and JSON datasets are in the same directory as the notebooks for seamless execution.
## 📊 Visualizations
The notebooks include the following visualizations:
- Customer Churn Rate by demographic factors.
- Heatmap of correlations between financial variables.
- ROC Curves for model comparison.
## 👨‍💻 Author
Dat Nguyen <br>
Email: ngvdat.w@gmail.com <br>
GitHub: github.com/vdat-18
