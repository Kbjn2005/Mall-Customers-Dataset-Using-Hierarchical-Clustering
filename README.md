# Mall Customers Dataset Clustering Using Hierarchical Clustering

## Project Overview
This project focuses on **customer segmentation and pattern analysis** using the **Mall Customers Dataset** through **Hierarchical Clustering**, an unsupervised machine learning technique.

Hierarchical clustering groups customers based on similarity without requiring predefined labels, helping to understand customer behavior and identify meaningful segments for business and marketing strategies.

---

## Objectives
- To analyze customer data from a mall dataset
- To apply hierarchical clustering for customer segmentation
- To visualize customer groupings using dendrograms
- To identify patterns in customer behavior

---

## Dataset Description
The dataset used in this project is **Mall_Customers.csv**.

### Dataset Characteristics
- Type: Structured tabular data
- Domain: Retail / Customer Analytics
- Learning Type: Unsupervised Learning
- Task: Clustering
- Format: CSV

Each row represents a customer, and each column represents a customer attribute.

### Common Columns in the Dataset
- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1–100)  

The dataset is loaded using the Pandas library.

```python
import pandas as pd
data = pd.read_csv('Mall_Customers.csv')
