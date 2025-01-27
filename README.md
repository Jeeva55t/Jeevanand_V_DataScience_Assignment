# Jeevanand_V_DataScience_Assignment
# eCommerce Transactions Analysis
# Zeotap
This repository contains a comprehensive data science project focused on analyzing an eCommerce transactions dataset. The project includes exploratory data analysis (EDA), building a Lookalike Model, and performing customer segmentation using clustering techniques.

## Dataset Description

The project utilizes three CSV files:

1. **Customers.csv**
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Continent where the customer resides.
   - `SignupDate`: Date of customer signup.

2. **Products.csv**
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price in USD.

3. **Transactions.csv**
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.
   - `Price`: Price of the product sold.

## Project Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- Performed EDA on the dataset to uncover trends and patterns.
- Generated 5 actionable business insights based on the analysis.

**Deliverables:**
- `Jeevanand_V_EDA.ipynb`: Jupyter Notebook containing the EDA code.
- `Jeevanand_V_EDA.pdf`: PDF report with business insights.

---

### Task 2: Lookalike Model
- Built a Lookalike Model to recommend 3 similar customers for a given customer based on their profile and transaction history.
- Used customer and product information to calculate similarity scores.

**Deliverables:**
- `Jeevanand_V_Lookalike.ipynb`: Jupyter Notebook with model development and recommendations.
- `Jeevanand_V_Lookalike.csv`: CSV file mapping Customer IDs to their top 3 lookalikes and similarity scores.

---

### Task 3: Customer Segmentation (Clustering)
- Performed customer segmentation using clustering algorithms.
- Utilized both customer profiles and transaction history for clustering.
- Evaluated clustering using the Davies-Bouldin (DB) Index and visualized the clusters.

**Deliverables:**
- `Jeevanand_V_Clustering.ipynb`: Jupyter Notebook containing clustering code.
- `Jeevanand_V__Clustering.pdf`: PDF report summarizing clustering results, metrics, and visualizations.

---

## How to Run the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/Jeeva55t/Jeevanand_V_DataScience_Assignment/tree/main
   
