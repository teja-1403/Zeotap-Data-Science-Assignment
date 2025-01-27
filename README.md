# Data Science Assignment: eCommerce Transactions Dataset

## Overview
This repository contains the deliverables for the Data Science assignment focused on analyzing an eCommerce Transactions dataset. The goal of the project is to perform exploratory data analysis (EDA), build predictive models, and derive actionable insights to improve business strategy.

---

## Dataset Description
The dataset consists of three files:
1. **[Customers.csv](https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing)**  
   - **CustomerID**: Unique identifier for each customer.  
   - **CustomerName**: Name of the customer.  
   - **Region**: Continent where the customer resides.  
   - **SignupDate**: Date when the customer signed up.  

2. **[Products.csv](https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing)**  
   - **ProductID**: Unique identifier for each product.  
   - **ProductName**: Name of the product.  
   - **Category**: Product category.  
   - **Price**: Product price in USD.  

3. **[Transactions.csv](https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing)**  
   - **TransactionID**: Unique identifier for each transaction.  
   - **CustomerID**: ID of the customer who made the transaction.  
   - **ProductID**: ID of the product sold.  
   - **TransactionDate**: Date of the transaction.  
   - **Quantity**: Quantity of the product purchased.  
   - **TotalValue**: Total value of the transaction.  
   - **Price**: Price of the product sold.  

---

## Tasks and Deliverables

### **Task 1: Exploratory Data Analysis (EDA) and Business Insights**
Perform EDA on the dataset to derive actionable insights.  
**Deliverables:**
- A Jupyter Notebook (`FirstName_LastName_EDA.ipynb`) containing EDA code.
- A PDF report (`FirstName_LastName_EDA.pdf`) summarizing key business insights.

### **Task 2: Lookalike Model**
Develop a model to recommend 3 similar customers for a given user based on profile and transaction history.  
**Deliverables:**
- A CSV file (`FirstName_LastName_Lookalike.csv`) with mappings: `Map<cust_id, List<cust_id, score>>`.
- A Jupyter Notebook (`FirstName_LastName_Lookalike.ipynb`) explaining the model development.

### **Task 3: Customer Segmentation / Clustering**
Perform customer segmentation using clustering techniques and evaluate using metrics like the Davies-Bouldin Index.  
**Deliverables:**
- A report (`FirstName_LastName_Clustering.pdf`) summarizing clustering results and metrics.
- A Jupyter Notebook (`FirstName_LastName_Clustering.ipynb`) containing clustering code and visualizations.

---

## Evaluation Criteria
### Task Breakdown:
| Task                          | Weightage |
|-------------------------------|-----------|
| Exploratory Data Analysis      | 25%       |
| Business Insights              | 15%       |
| Lookalike Model                | 30%       |
| Customer Segmentation          | 30%       |

**Ensure adherence to file formats and naming conventions for automated evaluation.**

---

Good luck with your assignment! 🚀
