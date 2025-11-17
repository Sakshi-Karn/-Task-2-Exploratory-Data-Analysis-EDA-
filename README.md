📊 Exploratory Data Analysis (EDA) – Supermarket Sales Dataset

This project performs a complete Exploratory Data Analysis (EDA) on the Supermarket Sales dataset using Python. The goal is to uncover meaningful business insights, understand data patterns, identify outliers, analyze correlations, and summarize customer and sales behavior across branches.

🛠️ Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook


🔍 Key Analysis Steps

The notebook covers the following EDA components:

1. Data Understanding

Dataset shape, info, data types

Summary statistics

Missing value analysis

Categorical value counts

2. Missing Data Visualization

Heatmap using sns.heatmap()

(Dataset contains no missing values)

3. Distribution Analysis

Histograms + KDE plots

Boxplots for outlier detection

Skewness analysis

4. Categorical Analysis

Countplots for:

Product line

Gender

Branch

Payment method

5. Correlation Analysis

Correlation matrix

Heatmap to visualize relationships

6. Business Insights (Groupby Analysis)

Revenue by product line

Revenue by branch

Gender-based sales comparison

Average rating per product line

7. Outlier & Skewness Check

IQR method for outlier detection

Log transform applied to skewed variables (optional)

📈 Summary of Findings

No missing values in the dataset; data is clean and complete.

Revenue varies significantly across product lines and branches.

Payment preferences show clear dominance of certain payment modes.

No strong correlations among numerical variables.

Monetary variables are right-skewed, indicating high-spending outliers.

Customer rating does not strongly correlate with sales or revenue.

📎 Project Outcome

This EDA helps identify:

Key revenue-generating product segments

Branch performance differences

Customer purchasing behavior

Data quality and distribution issues

The insights can support better decision-making in:

Inventory management

Product promotion

Branch-level optimization

Customer experience strategies
