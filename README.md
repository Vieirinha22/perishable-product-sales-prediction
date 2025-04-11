# 🛒 Predicting Sales of Discounted Perishable Products

## 📌 Project Overview
This project was developed as part of the Data Science & Business Analytics course at EDIT.  
It aims to analyze the effectiveness of discount strategies on perishable products near their expiration date, and to predict whether a product will be sold before expiring.

## 📊 Dataset
The dataset contains historical sales data (a bit over one month) from a national supermarket chain with the following features:
- Product ID, SKU, Brand
- Price (before and after discount)
- Weight, Profit Margin
- Percentage of expiring SKUs (perc_expiring)
- Dates: Expiration, Labeling, Sale (if applicable)
- Target variable: Sold or Not Sold

> ⚠️ **Note:** Due to confidentiality, the dataset cannot be shared publicly.

## 🛠️ Tools & Technologies
- Python (pandas, numpy, scikit-learn, matplotlib, seaborn, sklearn)
- Jupyter Notebook
- Power BI (for exploratory dashboards)

## 🧪 Model Building
Several classification models were tested, including:
- Logistic Regression
- Decision Tree Regrassion
- Random Forest

**Best performance:**  
Random Forest with ~73% accuracy and balanced precision/recall.

## 📈 Key Insights
- The inclusion of clusters in the predictive classification model did not help to improve the model's performance
- The store area, average expected profit per sku over the last 3 days and average 'period_expiring_vs_labelling' over the last 3 days by sky were top predictors.

