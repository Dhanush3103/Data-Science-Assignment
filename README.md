# Data-Science-Assignment
# **Customer Analytics Project**

This repository contains the code and reports for a customer analytics project, which includes three tasks:
1. **Exploratory Data Analysis (EDA)**
2. **Lookalike Model**
3. **Customer Segmentation using Clustering**

## **Repository Contents**
- `FirstName_LastName_EDA.pdf`: Report summarizing the EDA and business insights.
- `FirstName_LastName_EDA.ipynb`: Jupyter Notebook containing the EDA code.
- `FirstName_LastName_Lookalike.csv`: Lookalike model results (top 3 lookalikes for each customer).
- `FirstName_LastName_Lookalike.ipynb`: Jupyter Notebook explaining the lookalike model development.
- `FirstName_LastName_Clustering.pdf`: Report on clustering results with metrics and visualizations.
- `FirstName_LastName_Clustering.ipynb`: Jupyter Notebook containing clustering code.

---

## **Project Overview**
This project leverages customer and transaction data to derive actionable insights and build predictive models for a retail business.

### **1. Exploratory Data Analysis (EDA)**
- **Objective**: Analyze customer and transaction data to uncover trends and patterns.
- **Key Insights**:
  - Trends in customer signups and transaction behaviors.
  - Most popular product categories and customer regions.
  - Average transaction values and high-value customers.

### **2. Lookalike Model**
- **Objective**: Build a model to recommend similar customers based on profiles and transaction history.
- **Methodology**:
  - Used customer profiles and product preferences.
  - Employed `CountVectorizer` and `Cosine Similarity` to calculate similarity scores.
- **Deliverable**: A CSV file listing the top 3 lookalike customers for each of the first 20 customers.

### **3. Customer Segmentation (Clustering)**
- **Objective**: Segment customers into groups to identify unique clusters based on their profile and transaction data.
- **Clustering Algorithm**: K-Means Clustering.
- **Metrics**:
  - Davies-Bouldin Index: *e.g., 1.161*
  - Silhouette Score: *e.g., 0.254*
- **Visualizations**: Cluster plots showing customer segments.


---

## **Technologies Used**
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Tools**: Jupyter Notebook
