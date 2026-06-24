# Task 1: Supermart Sales Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on Supermart retail sales data using Microsoft Excel. The objective is to evaluate sales performance, identify key revenue drivers, and uncover trends to support business decision-making.

## Tasks Performed
- Data cleaning and preprocessing
- Sales analysis by category
- Sales analysis by city
- Time series analysis (sales trends over time)
- Data visualization using charts
- Insight generation and recommendations

## Tools and Techniques
- Microsoft Excel
- Pivot Tables
- Bar Charts
- Line Charts
- Data analysis and visualization

## Key Insights
- Sales showed a consistent upward trend from 2015 to 2018, indicating steady business growth.
- Eggs, Meat and Fish generated the highest revenue among all categories.
- Kanyakumari and Vellore were identified as top-performing cities.
- Sales peaked during September to December, showing strong seasonal demand.
- Lower sales were observed during January and February, indicating seasonal slowdown.

## Recommendations
- Focus marketing campaigns during peak months to maximize revenue.
- Increase inventory for high-performing categories.
- Improve sales strategies in underperforming cities.
- Use seasonal trends to plan discounts and promotional campaigns.
- Analyze customer behavior for personalized marketing strategies.

## Conclusion
The analysis highlights clear growth trends, seasonal patterns, and regional performance differences. These insights support data-driven decision-making.


# Task 2: Customer Segmentation using K-Means

## Project Overview
This project focuses on customer segmentation using K-Means clustering. The goal is to group customers based on purchasing behavior and demographics to improve marketing strategies.

## Dataset
- Income
- Age
- Purchase behavior
- Product spending

## Steps Performed
1. Data collection: Loaded the dataset using pandas
2. Data exploration: Used head(), info(), describe()
3. Feature engineering:
   - Total spending (MntTotal)
   - Total purchases
   - Engagement rate
4. Data preprocessing: Applied StandardScaler
5. Clustering: Implemented K-Means algorithm
6. Visualization: Used scatter plots
7. Insights: Identified customer segments

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Results
- Identified high-value customers
- Identified low-engagement customers
- Created useful customer segments for targeted marketing

## Conclusion
Customer segmentation helps businesses understand customer behavior and improve marketing effectiveness.


# Task 2: Credit Card Fraud Detection using Machine Learning

## Project Overview
This project aims to identify fraudulent credit card transactions using machine learning techniques. Fraud detection is a critical problem in financial systems, especially because fraudulent transactions are extremely rare compared to normal ones. This imbalance makes the task more challenging and requires careful handling during model development.

## Dataset Information
The dataset consists of anonymized credit card transaction records.

* Most features are transformed using PCA for privacy reasons
* The dataset is highly imbalanced

**Target Variable:**
* `0` → Legitimate Transaction
* `1` → Fraudulent Transaction

## Steps Performed

### 1. Exploratory Data Analysis
* Analyzed the distribution of transactions
* Observed the imbalance between fraud and normal cases
* Visualized patterns using graphs and plots

### 2. Handling Class Imbalance
* Used upsampling techniques to balance the dataset
* Ensured the model learns equally from both classes

### 3. Feature Engineering
* Created additional features based on transaction amount
* Applied scaling to normalize data for better model performance

### 4. Model Development
* Built a classification model using Logistic Regression
* Trained the model on the processed dataset

### 5. Model Evaluation
* Evaluated performance using:
  * Confusion Matrix
  * Classification Report
* Special focus was given to **recall**, as detecting fraud cases is more important than overall accuracy

### 6. Anomaly Detection
* Implemented Isolation Forest algorithm
* Detected unusual and suspicious transaction patterns

### 7. Real-Time Prediction Simulation
* Simulated predictions on new transaction inputs
* Classified transactions instantly as fraud or normal

## Tools and Technologies
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Results
* Achieved strong recall in detecting fraudulent transactions
* Successfully captured most fraud cases despite dataset imbalance
* Demonstrated the effectiveness of combining classification and anomaly detection techniques

## How to Use the Dataset
1. Download the dataset in ZIP format
2. Extract the files
3. Load `creditcard.csv` into the notebook
   
## Conclusion
This project highlights how machine learning can be applied to real-world fraud detection problems. By properly handling imbalanced data and focusing on recall, the model becomes more effective in identifying fraudulent activities. The combination of supervised learning and anomaly detection further improves the overall performance.

## Conclusion
This project highlights how machine learning can be applied to real-world fraud detection problems. By properly handling imbalanced data and focusing on recall, the model becomes more effective in identifying fraudulent activities. The combination of supervised learning and anomaly detection further improves the overall performance.

