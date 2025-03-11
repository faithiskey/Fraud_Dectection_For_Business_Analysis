-Fraud Detection Using Machine Learning

##Overview

Fraud detection is a critical application of machine learning, helping businesses prevent financial losses. This project explores fraud detection using Python, Pandas, NumPy, and Matplotlib.

## Dataset Features

1) trans_date_trans_time – The date and time of the transaction.

2)  merchant – The name of the merchant where the transaction took place.

3)  category – The type of business or industry the merchant belongs to (e.g., grocery, shopping, health).

4)  amt – The amount of money spent in the transaction.

5) city – The city where the transaction occurred.

6) state – The state where the transaction occurred.

7) lat – The latitude coordinate of the transaction location.

8) long – The longitude coordinate of the transaction location.

9) city_pop – The population of the city where the transaction took place.

10) job – The occupation of the person making the transaction.

11) dob – The date of birth of the person making the transaction.

13) trans_num – A unique identifier for each transaction.

14) merch_lat – The latitude coordinate of the merchant’s location.

15) merch_long – The longitude coordinate of the merchant’s location.

16) is_fraud – A binary indicator (0 or 1) where 1 means the transaction is fraudulent.

🚀 In this project, I explored how machine learning can accurately detect fraudulent transactions, improving financial security.

🔹 Here’s a breakdown of the process, insights, and results:

🛸 Objective
The goal was to develop predictive modeling for businesses, enabling early fraud detection and enhancing financial security.

🔍 Steps Taken:
📌 Data Loading & Exploration
 ⭐ Dataset includes transaction details: date, merchant, category, amount, location, and user demographics.

📌 Exploratory Data Analysis (EDA)
 ⭐ Checked data types, missing values, and key statistics (e.g., df.info(), df.describe(), df.isnull().sum()).

📌 Feature Engineering
 ⭐ Converted transaction date to a datetime format
 ⭐ Extracted hour of transaction to analyze fraud trends over time

📊 Data Visualizations & Key Insights
⭐ Fraud vs. Non-Fraud Transactions (Boxplot)
 ⚡ Higher Median Amounts – Fraudulent transactions tend to have higher values.
 ⚡ Wide Interquartile Range (IQR) – Fraud transactions show more variability in amounts.
 ⚡ Outliers – Extreme transaction amounts could indicate fraudulent activity.

⭐ Fraud Distribution by Category
 ⚡ Identifies high-risk transaction types (e.g., online shopping, luxury purchases).
 ⚡ Categories with higher fraud rates may need stricter security measures.

⭐ Fraud Distribution Over Hours
 ⚡ Peak Fraud Hours – Higher fraud rates may occur at night when monitoring is lower.
 ⚡ Business Implications – Financial institutions can allocate fraud prevention resources accordingly.

📌 Model Training: Random Forest Classifier
For this project, I used a Random Forest Classifier, a powerful ensemble learning method. It was chosen because it:
✅ Handles complex, non-linear fraud patterns
 ✅ Ranks important features to improve detection
 ✅ Works well with imbalanced datasets and reduces overfitting

📊 Key Steps in the Model
 1️⃣ Data Preprocessing – Standardizing numerical features & encoding categorical data
 2️⃣ Train-Test Split – 70% training, 30% testing
 3️⃣ Model Training – Using 100 decision trees to classify transactions
 4️⃣ Predictions – Identifying fraud cases from test data
 5️⃣ Evaluation – Achieved 96% accuracy, showing strong fraud detection performance

💡 Machine learning is transforming fraud detection, helping businesses prevent financial losses and protect customers.
