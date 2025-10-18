# **Customer Segmentation Project**

## **Project Overview**
Customer segmentation is a crucial process for understanding and analyzing customer behavior. This project focuses on grouping customers based on their **purchasing behavior**, particularly using **Annual Income** and **Spending Score**. By applying **K-Means clustering**, distinct customer segments are identified, helping businesses design targeted marketing strategies and personalized offers.

> **Note:** The data has been preprocessed to handle missing values, and irrelevant columns such as **CustomerID** were ignored during analysis.

---

## **Methodology**

### **1. Data Cleaning & Preprocessing**
- Checked for missing values  
- Removed irrelevant columns (CustomerID)  
- Categorized **Age** into meaningful groups  

### **2. Exploratory Data Analysis (EDA)**
- Visualized **Number of Customers vs Age Groups**  
- Visualized **Number of Customers vs Gender**  
- Explored **Annual Income vs Spending Score**  

### **3. K-Means Clustering**
- Determined the optimal number of clusters using the **Elbow Method (WCSS)**  
- Trained the K-Means model on **Annual Income** and **Spending Score**  
- Identified **5 customer segments**:  
  - **Budget Customers:** Low Income, Low Spending  
  - **Premium Customers:** High Income, High Spending  
  - **Average Customers:** Medium Income, Medium Spending  
  - **Savers:** High Income, Low Spending  
  - **Impulsive Customers:** Low Income, High Spending  

### **4. Visualization**
- Scatter plot of **Annual Income vs Spending Score** colored by clusters  
- Bar plots for **Age Groups** and **Gender** distribution  
- Cluster centroids highlighted for easy interpretation  

---

## **Insights**
- **Low Income & Low Spending**  These customers usually make cautious purchase decisions and are highly price-sensitive. They often buy only necessary items and respond well to discounts and promotions.  
- **High Income & High Spending** customers are the most profitable and ideal for premium products. 
- **High Income & High Spending** These customers exhibit balanced purchasing behavior, buying both essential and non-essential products moderately.  
- **Low Income & High Spending** customers are impulsive buyers, responsive to discounts or promotions.  
- **High Income & Low Spending** customers are savers; they might need incentives to increase spending.  
- Age and Gender distribution visualizations provide demographic insights for targeted campaigns.  

---

## **Tools & Libraries**
- **Python 3**  
- **Pandas** – Data manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – K-Means clustering  

---

## **Conclusion**
This project demonstrates how **customer segmentation** can provide actionable insights for businesses. By analyzing purchasing behavior through **Annual Income** and **Spending Score**, companies can design effective marketing strategies, allocate resources efficiently, and enhance customer satisfaction.

---


