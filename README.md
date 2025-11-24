# Customer Segmentation Using Unsupervised Machine Learning

## Overview

This project demonstrates an end-to-end, real-world application of **customer segmentation** for a grocery retailer using Python and unsupervised learning. The goal is to leverage customer data (demographics, spending, and campaign responses) to identify actionable customer segments and deliver tailored business strategies for each one.


## Problem Statement

Retailers often collect extensive customer data but face challenges using it to drive targeted marketing and personalized offers.  
**This project answers:**  
> "How can we segment customers in a data-driven, actionable way to design precise marketing strategies and improve customer engagement and revenue?"



## Project Notebook

All code, EDA, and analysis are contained in:  
**[Unsupervised_Learning_Project_2.ipynb](Unsupervised_Learning_Project_2.ipynb)**

- **What It Covers:**
  - Data loading, cleaning, exploratory data analysis (EDA)
  - Feature engineering: Age, total spend, family size, tenure, categorical encoding
  - Outlier detection and treatment
  - Dimensionality reduction using PCA
  - Unsupervised clustering (elbow method & Agglomerative Clustering)
  - In-depth cluster profiling and visualization
  - Marketing recommendations for each customer segment
- **How To Use:**
  - Launch the notebook in Jupyter or Google Colab.
  - Follow the step-by-step cells (with markdown explanations) from raw data to business-ready insights.



## Workflow

1. **Data Loading & Exploration**
   - Imported and analyzed customer demographic and transaction data.
   - Handled missing values and data type inconsistencies.

2. **Data Cleaning & Feature Engineering**
   - Filtered out outliers in age and income.
   - Engineered new features: actual age, total spend, family size, parental status, customer tenure, education level.
   - Encoded categorical variables for modeling.

3. **Preprocessing & Reduction**
   - Scaled features for normalization.
   - Applied Principal Component Analysis (PCA) to aid clustering and visualization.

4. **Clustering (Unsupervised Learning)**
   - Used the elbow method to identify optimal cluster count.
   - Performed Agglomerative Clustering to assign customers to segments.

5. **Cluster Profiling & Business Recommendations**
   - Interpreted each cluster's demographics, spending habits, and campaign response.
   - Developed targeted marketing strategies tailored to each segment.


## Customer Cluster Profiling & Strategies

### **Cluster 0: Older Parents, Medium/Large Families (Teens)**

- **Profile:** Parents, family size 2–4 (incl. single parents & teens), relatively older.
- **Strategy:** Family value packs, multi-buy discounts, ready-meal kits, traditional/digital marketing.

### **Cluster 1: Younger Parents, Small Families (Baby/Toddler)**

- **Profile:** Younger parents, family size 2–3, mostly with one young child (not teens).
- **Strategy:** Focus on fresh produce/organic baby items, social media/app coupons, family-friendly instore events.

### **Cluster 2: High-Income Couples/Singles, No Children**

- **Profile:** Not parents, family size 1–2 (mostly couples), high income, all ages.
- **Strategy:** Premium & specialty foods, unique shopping experiences, premium newsletters/bundle kits.

### **Cluster 3: Older, Low-Income, Large Families (Teens)**

- **Profile:** Parents, family size 2–5, mostly with teens, older, lower income.
- **Strategy:** Store brands, big volume discounts, weekly sale circulars, high-value loyalty rewards.


## Outcome

- Successfully segmented customers into actionable clusters.
- Produced data-driven business strategies optimized for engagement, satisfaction, and revenue.
- Delivered a repeatable workflow for any retail or customer analytics scenario.


## Technologies Used

- Python (Jupyter/Colab)
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn


## Conclusion

By turning raw customer data into well-defined segments and marketing actions, this project demonstrates the impact of applied machine learning in retail analytics.  
**Targeted marketing means happier customers and smarter business growth.**

