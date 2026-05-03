**Supply Chain Delivery Performance Analysis**
This project presents an end-to-end data analysis and machine learning solution focused on identifying and solving delivery delays in a global e-commerce supply chain.

The analysis is based on 172,000+ orders and aims to uncover operational inefficiencies, quantify financial impact, and build a predictive system to improve delivery performance.

**Problem Statement**
A global e-commerce company is facing inconsistent delivery performance, with actual shipping times deviating from scheduled timelines. 
This results in:
High late delivery rates
Reduced customer trust
Loss in profitability
Inefficient operational decision-making

**Objectives**
Analyze delivery performance across regions, shipping modes, and time
Identify key bottlenecks causing delays
Measure financial impact of late deliveries
Build a predictive model to identify high-risk (late) orders
Provide actionable business recommendations

**Key Insights**
54.71% of orders are delayed → systemic issue
$2.1M profit at risk due to delayed deliveries
First Class shipping shows 100% delay rate
Delay patterns are consistent across regions → global inefficiency
Peak delays occur during Aug, Sep, and Dec

**Machine Learning Model**
Model: Random Forest Classifier
Accuracy: 74%
Precision (Late Orders): 78%
Recall (Late Orders): 75%

The model helps predict whether an order will be delayed before shipping, enabling proactive decision-making.

**Tech Stack**
Python (Pandas, NumPy)
Data Visualization (Matplotlib, Seaborn)
Machine Learning (Scikit-learn)
Data Processing (SMOTE for class imbalance)
Jupyter Notebook

**Key Features**
Data cleaning & preprocessing pipeline
Feature engineering (delay, time-based features)
Exploratory Data Analysis (EDA)
KPI and profitability analysis
Delay distribution & bottleneck detection
Predictive modeling pipeline

**Business Recommendations**
Fix shipping mode allocation (critical issue)
Deploy predictive alert system
Improve payment processing workflows
Plan capacity for seasonal demand spikes
Optimize logistics for high-delay regions
