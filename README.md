
# Customer Clustering Project

## 1. Business Problem
### 1.1 Problem Context 

Our client is a UK-based online retailer specializing in all-occasion gifts, primarily serving wholesalers. While the majority of their customers are based in the UK, a small percentage of their clientele is international. The retailer is seeking to group these international customers based on their purchasing patterns in order to provide tailored services and improve targeted marketing efforts.

### 1.2 Problem Statement

The retailer has engaged us to develop customer segments (or "clusters") through a data-driven approach. We will create a clustering model using past transactional data to capture aggregate sales behavior and item-specific purchasing patterns.

### 1.3 Business Objectives and Constraints

Objective: Develop meaningful customer segments based on purchasing behavior.
Constraints: The solution must be scalable and actionable, providing insights that can inform marketing strategies and customer services.

## 2. Machine Learning Problem
### 2.1 Data Overview

The dataset contains 35,116 records of past international transactions spanning 37 countries. This is an unsupervised learning problem with no target variable provided. The dataset includes the following features:

### Invoice Information
**InvoiceNo**: Unique identifier for each invoice  
**InvoiceDate**: Date of the invoice  
#### Item Information  
**StockCode**: Unique identifier for each item  
**Description**: Text description of the item  
**Quantity**: Number of units per pack  
**UnitPrice**: Price per unit (GBP)  
#### Customer Information  
**CustomerID**: Unique identifier for each customer  
**Country**: Customer's country of origin  

### 2.2 Mapping the Business Problem to the ML Problem  
#### 2.2.1 Type of ML Problem
This is an unsupervised learning problem. We need to segment customers based on their transaction data. Although the dataset is transaction-level, the goal is to create customer-level clusters based on purchasing patterns across multiple transactions.

