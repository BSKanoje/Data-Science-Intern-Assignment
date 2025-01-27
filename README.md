# **eCommerce Data Science Assignment**

## **Overview**
This repository contains the deliverables for the eCommerce Data Science Assignment. The project involves analyzing transactional data, building a lookalike model, and performing customer segmentation to derive actionable insights and improve business strategies.

---

## **Dataset Description**
### **1. Customers.csv**
- **CustomerID**: Unique identifier for each customer.  
- **CustomerName**: Name of the customer.  
- **Region**: Continent where the customer resides.  
- **SignupDate**: Date when the customer signed up.

### **2. Products.csv**
- **ProductID**: Unique identifier for each product.  
- **ProductName**: Name of the product.  
- **Category**: Product category.  
- **Price**: Product price in USD.

### **3. Transactions.csv**
- **TransactionID**: Unique identifier for each transaction.  
- **CustomerID**: ID of the customer who made the transaction.  
- **ProductID**: ID of the product sold.  
- **TransactionDate**: Date of the transaction.  
- **Quantity**: Quantity of the product purchased.  
- **TotalValue**: Total value of the transaction.  
- **Price**: Price of the product sold.

---

## **Tasks**
### **Task 1: Exploratory Data Analysis (EDA) and Business Insights**
1. Perform EDA on the datasets to understand data distributions, correlations, and trends.  
2. Derive at least **5 business insights** from the EDA.

#### **Deliverables**
- `FirstName_LastName_EDA.ipynb`: Jupyter Notebook with EDA code.  
- `FirstName_LastName_EDA.pdf`: PDF report with business insights.

---

### **Task 2: Lookalike Model**
1. Build a Lookalike Model to recommend **3 similar customers** based on profile and transaction history.  
2. Assign similarity scores to each recommendation.

#### **Deliverables**
- `FirstName_LastName_Lookalike.ipynb`: Jupyter Notebook explaining the model development.  
- `FirstName_LastName_Lookalike.csv`: CSV file with mappings of `CustomerID` and their top 3 lookalikes with similarity scores.

---

### **Task 3: Customer Segmentation / Clustering**
1. Perform customer segmentation using clustering techniques.  
2. Use customer profile and transaction data.  
3. Calculate clustering metrics (e.g., DB Index) and visualize the clusters.

#### **Deliverables**
- `FirstName_LastName_Clustering.ipynb`: Jupyter Notebook with clustering code.  
- `FirstName_LastName_Clustering.pdf`: Report with clustering results, DB Index, and visualizations.
