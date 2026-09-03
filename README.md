Customer Churn Analysis

Author

Padamata Hema Mani Chandra

📊 Project Overview

Customer Churn Analysis is a data analytics and Business Intelligence project focused on identifying the factors associated with customer churn in an e-commerce dataset.

The project analyzes and cleans 5,630 customer records, performs exploratory data analysis, compares multiple classification models, and converts the model predictions into customer risk tiers for visualization in Power BI.

The goal is to turn customer data into actionable insights that can help identify customers who may be at higher risk of leaving.

🎯 Objectives

Clean and prepare customer data for analysis.

Perform exploratory data analysis (EDA).

Identify important factors associated with customer churn.

Build and compare machine learning classification models.

Evaluate model performance using classification metrics.

Generate customer risk tiers from model predictions.

Present the results through a Power BI dashboard.

🛠️ Technologies Used

Programming

Python

SQL

Data Analysis

Pandas

NumPy

Data Visualization

Matplotlib

Seaborn

Power BI

Machine Learning

Scikit-learn

Logistic Regression

Decision Tree

Random Forest

Development Environment

Jupyter Notebook

Visual Studio Code

🔄 Project Workflow

Raw Customer Data
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Analysis
       ↓
Model Training
       ↓
Model Comparison
       ↓
Model Evaluation
       ↓
Customer Risk Tier Generation
       ↓
Power BI Dashboard

🧹 Data Cleaning & Preparation

The project begins with preparing the e-commerce customer dataset for analysis.

The workflow includes:

Inspecting the dataset

Cleaning customer records

Preparing relevant variables

Exploring customer behavior

Preparing data for machine learning

Creating the required inputs for customer risk analysis

🔎 Exploratory Data Analysis

EDA was performed to understand customer behavior and identify patterns associated with churn.

The analysis identified the following factors as important churn-related indicators:

Customer tenure

Customer complaints

Customer activity

Visual analysis was performed using Matplotlib and Seaborn.

🤖 Machine Learning Models

Three classification algorithms were compared:

1. Logistic Regression

Used as a baseline classification model for predicting customer churn.

2. Decision Tree

Used to capture non-linear relationships between customer characteristics and churn.

3. Random Forest

Used as an ensemble classification approach to improve predictive performance.

📈 Model Performance

The project achieved:

Metric

Result

Test Accuracy

98.05%

Churn-Class F1 Score

0.94

The models were compared to identify an effective approach for customer churn prediction.

🏷️ Customer Risk Tiers

The predictive-model outputs were transformed into customer risk tiers.

These risk tiers provide a business-friendly way to interpret model predictions and identify customers who may require additional attention.

The resulting risk information was prepared for visualization in Power BI.

📊 Power BI Dashboard

The machine learning outputs were exported into a format suitable for business intelligence analysis.

The Power BI component provides a visual representation of customer churn risk and helps communicate the analytical results in a business-friendly format.

Dashboard Focus

Customer churn insights

Customer risk tiers

Key churn-related factors

Model-driven customer insights

💡 Key Insights

The analysis identified:

Tenure as an important factor associated with customer churn.

Customer complaints as an important churn-related indicator.

Customer activity as another key factor associated with churn.

Machine learning can be used to transform customer behavior data into actionable risk information.

Power BI can help communicate predictive-model outputs to business users.

📁 Suggested Project Structure

Customer-churn-analysis/
│
├── data/
│   └── customer_data.csv
│
├── notebooks/
│   └── customer_churn_analysis.ipynb
│
├── models/
│   └── trained_models/
│
├── powerbi/
│   └── customer_churn_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── requirements.txt
└── README.md

Update the folder and file names above to match the actual repository structure.

⚙️ Installation

Clone the repository:

git clone https://github.com/urs-mani/Customer-churn-analysis.git

Move into the project directory:

cd Customer-churn-analysis

Install the required Python libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

▶️ Running the Analysis

Open the Jupyter Notebook:

jupyter notebook

Then open the Customer Churn Analysis notebook and run the cells sequentially.

📊 Project Results

The project successfully combines:

Data Cleaning → EDA → Machine Learning → Risk Classification → Business Intelligence

The final output transforms raw e-commerce customer records into predictive churn insights and customer risk tiers that can be explored through Power BI.

🔗 Repository

GitHub:
https://github.com/urs-mani/Customer-churn-analysis

👨‍💻 Author

Padamata Hema Mani Chandra

Final-year B.Tech Student | Aspiring Data Analyst

Interests:

Data Analytics

Machine Learning

Business Intelligence

Python

SQL

Power BI

Web Development

Mobile Application Development


⭐ If you find this project useful, feel free to explore the repository.
