# 🛒 Online Retail Customer Segmentation & Recommendation System

![UCI ML Repo](https://img.shields.io/badge/UCI-ML%20Repo-blue?style=for-the-badge&logo=databricks&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Anomaly Detection](https://img.shields.io/badge/Anomaly-Detection-red?style=for-the-badge&logo=anaconda&logoColor=white)
![PCA](https://img.shields.io/badge/Dimensionality%20Reduction-PCA-purple?style=for-the-badge&logo=python&logoColor=white)

---

## 📌 Project Overview
This project explores the **Online Retail dataset** from a UK-based retailer, sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail).  
The dataset documents all transactions occurring between **2010 and 2011**.

Our primary objectives are:
- ✅ **Customer Segmentation** using **K-means clustering**.  
- ✅ **Recommendation System** to suggest **top-selling products** to customers who haven’t purchased them yet.  
- ✅ Enhance marketing strategies and increase sales by understanding **customer behavior**.  

---

## 📂 Dataset Information

| __Variable__   | __Description__ |
|     :---       |       :---      |      
| __InvoiceNo__  | Code representing each unique transaction. If this code starts with letter 'C', it indicates a cancellation. |
| __StockCode__  | Code uniquely assigned to each distinct product. |
| __Description__| Description of each product. |
| __Quantity__   | The number of units of a product in a transaction. |
| __InvoiceDate__| The date and time of the transaction. |
| __UnitPrice__  | The unit price of the product in sterling. |
| __CustomerID__ | Identifier uniquely assigned to each customer. |
| __Country__    | The country of the customer. |

---

## 🛠️ Methodology

1. **Data Preprocessing**
   - Handling missing values, cancellations, and duplicates  
   - Feature engineering to create customer-level metrics (Recency, Frequency, Monetary — *RFM*)  

2. **Unsupervised Learning**
   - Dimensionality reduction with **PCA**  
   - **K-means clustering** to segment customers  

3. **Anomaly Detection**
   - Using **Isolation Forest** to identify abnormal purchasing behavior  

4. **Recommendation System**
   - Recommending top-selling products in each cluster to customers who haven’t purchased them  

---

## 📊 Expected Outcomes
- **Customer Profiles**: Group customers into distinct segments (e.g., high-value, frequent buyers, occasional buyers).  
- **Anomaly Insights**: Detect unusual purchasing behaviors (e.g., bulk purchases, returns).  
- **Actionable Marketing**: Recommend products tailored to each cluster, improving **engagement & sales**.  

---

## 🚀 Tech Stack
- **Python** 🐍  
- **Pandas / NumPy** for data preprocessing  
- **Matplotlib / Seaborn** for visualization  
- **Scikit-learn** for clustering, PCA & anomaly detection  

---

## 📎 Reference
Dataset: [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)

---
