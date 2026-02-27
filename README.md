# PROJET-DATA-ANALYSS-BMW
This project presents an end-to-end data analysis of BMW vehicle data with the goal of understanding sales behavior, pricing, and marketing efficiency across different vehicle categories.
The focus is on transforming raw data into clear insights and actionable business recommendations.

This project was built as part of my learning journey in data analysis and reflects both technical skills and analytical thinking.

📊 Dataset Description

The dataset contains information related to BMW vehicles, including:

Vehicle type (EV, SUV, Sedan)

Price

Revenue

Marketing cost

Year

Data Challenges:

Missing values in some columns

Large-scale numerical values (millions) that required normalization

Mixed data types requiring correction

🧹 Data Cleaning

The data cleaning process focused on ensuring reliability and consistency:

Handling missing values

Normalizing large numerical values for better readability and comparison

Correcting data types

Removing inconsistencies that could affect analysis results

Goal: Prepare clean and trustworthy data before analysis.

📈 Exploratory Data Analysis (EDA)

EDA was performed to understand patterns and trends in the data:

Distribution of vehicle prices

Revenue trends over time

Comparison of performance across vehicle categories

Marketing cost vs revenue behavior

Visualizations were used to support interpretation and decision-making.

🛠️ Feature Engineering

Basic feature engineering techniques were applied:

Aggregations using groupby

Comparison metrics between vehicle categories

Indicators related to marketing efficiency

The focus was on interpretability rather than complexity.

📉 PCA (Educational Purpose)

Principal Component Analysis (PCA) was applied as a learning exercise to explore dimensionality reduction.

After evaluation:

PCA did not provide significant business value for this dataset

Most variance required multiple components

Interpretability was reduced

➡️ Conclusion: PCA was not used for decision-making, reinforcing the importance of choosing techniques based on business value, not complexity.

🔍 Key Insights

Electric vehicles show more stable marketing efficiency after 2020

SUVs and Sedans exhibit higher volatility in marketing performance

Higher price does not always translate into higher marketing efficiency

Marketing strategy appears to play a critical role in performance differences

💡 Business Recommendations

Reassess marketing strategies for Sedan and SUV categories to reduce performance volatility

Leverage successful marketing approaches used for Electric Vehicles where applicable

Focus on efficiency-driven decision-making rather than price alone

🎯 What I Learned

How to build an end-to-end data analysis pipeline

The importance of data cleaning before analysis

How to extract insights that support business decisions

When not to use advanced techniques like PCA

How to think beyond numbers and focus on decision impact

🧰 Tools & Technologies

Python

Pandas

NumPy

Matplotlib / Seaborn 

Scikit_Learn

Jupyter Notebook

📌 Final Note

This project reflects my current level as a Junior Data Analyst in training.
It demonstrates my ability to work with real datasets, think analytically, and continuously improve through practice.
