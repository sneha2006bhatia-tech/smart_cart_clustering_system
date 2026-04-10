#  SmartCart Customer Clustering System

##  Project Overview

This project focuses on building a customer segmentation system for an e-commerce platform called SmartCart. The goal is to group customers based on their behavior and purchasing patterns using unsupervised machine learning techniques.

Currently, many businesses use the same marketing strategy for all users, which is not efficient. In this project, I tried to solve this problem by identifying different types of customers so that businesses can take better decisions like targeted marketing and customer retention.



## Problem Statement

SmartCart has customer data but no clear segmentation strategy. This leads to:

* Inefficient marketing campaigns
* Poor customer targeting
* Difficulty in identifying loyal or churn-prone customers

This project aims to cluster customers into meaningful groups based on their activity and spending behavior.



## Dataset Description

The dataset contains around **2240 customer records** with multiple features such as:

* Demographics (age, education, income)
* Purchase behavior (amount spent on products)
* Shopping frequency (online, store, catalog)
* Website activity
* Customer feedback (complaints, recency)



##  Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

##  Machine Learning Approach

I applied **unsupervised learning techniques** to find patterns in the data:

* K-Means Clustering
* Hierarchical Clustering
* DBSCAN (for density-based clustering)

Steps followed:

1. Data cleaning and preprocessing
2. Feature selection and scaling
3. Applying clustering algorithms
4. Evaluating clusters using visualizations



##  Key Insights

* Customers can be grouped based on spending habits and engagement
* Some clusters represent high-value customers
* Some clusters indicate low engagement or potential churn
* These insights can help businesses personalize marketing strategies



##  Future Improvements

* Try more advanced clustering techniques
* Deploy model using a web app (Streamlit)
* Add real-time customer segmentation
* Improve feature engineering



## Project Structure

* `smart_cart_project.ipynb` → Main notebook
* `smart_cart.csv` → Dataset
* Other notebooks → Experiments with different clustering techniques



##  About Me

I am a beginner AI/ML developer currently learning machine learning and working on real-world projects to improve my skills.

---

##  Conclusion

This project helps to understand how unsupervised learning can be used in real-world business problems. It also improved my skills in data preprocessing, clustering, and data visualization.
