# Black Friday Sales - Exploratory Data Analysis (EDA)
**📚 Project Overview**
This project performs an exploratory data analysis (EDA) on the Black Friday Sales dataset provided by a retail company. The primary goal is to uncover meaningful patterns, customer behavior insights, and factors influencing purchase amounts during Black Friday sales.

The analysis includes data cleaning, feature engineering, univariate and bivariate analysis, and actionable insights that could help improve future marketing and sales strategies.

**📝 Dataset Information**
Source: Black Friday Sales Dataset - Kaggle

Size: ~550,000 rows

Features:

User_ID

Product_ID

Gender

Age

Occupation

City_Category

Stay_In_Current_City_Years

Marital_Status

Product_Category_1, Product_Category_2, Product_Category_3

Purchase (target variable)

**🛠️ Technologies Used**
Python (3.x)

Libraries:

pandas — Data manipulation

numpy — Numerical computations

matplotlib and seaborn — Data visualization

scikit-learn — Preprocessing (optional)

**📊 Key Steps in Analysis**
Data Loading
Import necessary libraries and load the dataset.

Data Cleaning

Handle missing values.

Correct data types if necessary.

Remove duplicates (if any).

Exploratory Data Analysis

Univariate Analysis: Understand distribution of each variable.

Bivariate Analysis: Explore relationships between features and Purchase.

Insights: Gender, Age, Occupation vs Purchase behavior.

Product Category Analysis: Popular products and their impact on sales.

**Feature Engineering**

Encode categorical features if needed for future modeling.

**Visualization**

Bar plots, histograms, box plots, and heatmaps to identify trends and correlations.

Insights and Recommendations

Key business insights based on analysis.

**🔍 Insights Summary**
1. Male customers contribute more to the total sales compared to female customers.

2. Younger age groups (26–35) are the most active shoppers.

3. City category 'B' customers show a higher purchase amount.

4. Certain product categories dominate the sales figures.

5. Longer stay in the city slightly correlates with higher purchase amounts.


🚀 How to Run the Project
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/black-friday-eda.git
Navigate to the project folder:

bash
Copy
Edit
cd black-friday-eda
Install required packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
📂 Folder Structure
bash
Copy
Edit

**📌 Future Work**
Apply machine learning models to predict purchase amounts.

Perform customer segmentation using clustering algorithms.

Build dashboards for real-time sales monitoring.

✨ Acknowledgements
Dataset sourced from Kaggle's Black Friday Sales Prediction Challenge.

Thanks to the open-source community for amazing libraries and tools!
