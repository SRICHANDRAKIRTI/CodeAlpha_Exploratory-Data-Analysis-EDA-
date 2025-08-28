🔍 Overview

The main objective of this task is to:

Ask meaningful questions about the dataset before analysis

Explore the structure of the dataset (variables, datatypes, shape)

Identify trends, patterns, and anomalies

Perform hypothesis testing and validate assumptions

Detect potential data quality issues (null values, errors)

📂 Dataset

The dataset used in this task is merged_index.csv, which contains information about coffee names, prices (money), and other attributes.

⚙️ Steps Performed

Data Loading

Imported the dataset using Pandas

Data Exploration

Displayed first and last few rows (head(), tail())

Checked data types and dataset info (info())

Generated statistical summary (describe())

Data Visualization

Bar plots to identify the most popular coffee types

Histograms to analyze distribution of prices

Hypothesis Testing

Performed t-test between Latte and Cocoa prices to check statistical difference

Data Quality Checks

Detected missing and null values

🛠️ Libraries Used

NumPy – Numerical operations

Pandas – Data manipulation and analysis

Matplotlib – Data visualization

SciPy – Hypothesis testing (t-test)

📈 Results & Insights

Coffee type distribution shows certain popular choices.

Price distributions differ across coffee categories.

Hypothesis testing provides insights into whether the price difference between coffee types is statistically significant.

Null values were detected and need to be handled for further analysis.

🚀 How to Run

Clone this repository

git clone <your-repo-link>


Open the Jupyter Notebook:

jupyter notebook Code_alpha_task2.ipynb


Run all cells to reproduce the analysis.

📌 Conclusion

This task gave hands-on practice in Exploratory Data Analysis (EDA), focusing on data exploration, visualization, statistical testing, and data quality checks. It forms the foundation for building deeper insights in future tasks.
