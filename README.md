# Data Science Assignment: eCommerce Transactions Dataset

## Overview
This project focuses on analyzing and deriving insights from an eCommerce Transactions dataset. The dataset consists of three CSV files: **Customers.csv**, **Products.csv**, and **Transactions.csv**, each providing crucial information about customers, products, and transactions. The tasks accomplished in this project include Exploratory Data Analysis (EDA), building a Lookalike Model, and performing Customer Segmentation using clustering techniques.

---

## Dataset Description
### 1. Customers.csv
- **CustomerID**: Unique identifier for each customer.  
- **CustomerName**: Name of the customer.  
- **Region**: Geographical region where the customer resides.  
- **SignupDate**: Date of customer signup.  

### 2. Products.csv
- **ProductID**: Unique identifier for each product.  
- **ProductName**: Name of the product.  
- **Category**: Product category.  
- **Price**: Price of the product in USD.  

### 3. Transactions.csv
- **TransactionID**: Unique identifier for each transaction.  
- **CustomerID**: Links the transaction to a customer.  
- **ProductID**: Links the transaction to a product.  
- **TransactionDate**: Date of the transaction.  
- **Quantity**: Quantity purchased.  
- **TotalValue**: Total value of the transaction.  

---

## Tasks Accomplished

### **Task 1: Exploratory Data Analysis (EDA)**
- Conducted a detailed analysis of the dataset, identifying key patterns and trends.  
- Derived **5 business insights**, such as customer purchasing behavior, top-performing regions, and product popularity.  
- Deliverables:  
  - Jupyter Notebook containing the EDA code.  
  - PDF report with concise business insights.  

### **Task 2: Lookalike Model**
- Built a **Lookalike Model** to recommend similar customers based on transaction and profile data.  
- Used customer and product features to calculate a similarity score for recommendations.  
- Generated a CSV file `Lookalike.csv`, mapping the top 3 lookalike customers (with scores) for the first 20 customers (CustomerID: C0001–C0020).  
- Deliverables:  
  - Jupyter Notebook explaining the model development.  
  - CSV file with the lookalike results.  

### **Task 3: Customer Segmentation**
- Performed customer segmentation using the **KMeans clustering algorithm**, leveraging both profile and transaction data.  
- Determined the optimal number of clusters using the **Elbow Method** and evaluated the clusters with the **Davies-Bouldin Index (DB Index)**.  
- Visualized clusters using **PCA** for a clear understanding of customer groups.  
- Key metrics:  
  - **Clusters formed**: 4  
  - **DB Index**: 1.22 (indicating good cluster separation)  
- Deliverables:  
  - Jupyter Notebook with clustering implementation and visualizations.  
  - PDF report summarizing clustering results.  

---
## Insights and Learnings
This project involved practical application of data science concepts, focusing on:
1. Cleaning and preprocessing raw datasets.  
2. Using clustering techniques to segment customers into actionable groups.  
3. Implementing recommendation systems to enhance customer targeting.  
4. Visualizing and interpreting data insights effectively.  

The results provide valuable input for business decisions, such as targeted marketing, personalized offers, and customer retention strategies.

---

## Next Steps
- Experiment with advanced clustering algorithms like **DBSCAN** or **Agglomerative Clustering**.  
- Incorporate additional features (e.g., demographic data) to enhance segmentation.  
- Optimize the Lookalike Model using advanced similarity measures or machine learning techniques.  
