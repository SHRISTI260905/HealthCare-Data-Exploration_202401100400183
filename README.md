# HealthCare-Data-Exploration_202401100400183

Healthcare Data Exploration

Overview

This project explores healthcare data by visualizing key health metrics such as blood pressure, sugar levels, and weight. The goal is to identify trends and correlations among these variables.

Prerequisites

Ensure you have Python installed along with the required libraries:

pip install pandas matplotlib seaborn

Dataset

The script uses a sample dataset containing the following attributes for 20 patients:

Patient ID: Unique identifier for each patient

Blood Pressure (mmHg): Patient's blood pressure readings

Sugar Level (mg/dL): Patient's blood sugar levels

Weight (kg): Patient's weight in kilograms

Features & Visualizations

Basic Statistics:

The script generates descriptive statistics using df.describe().

Pairplot Analysis:

A seaborn.pairplot is used to visualize overall trends among health parameters.

Blood Pressure Distribution:

A histogram with KDE overlay shows the distribution of blood pressure values.

Sugar Level vs. Weight Scatter Plot:

A scatter plot visualizes the relationship between weight and sugar levels, using blood pressure values for color and size differentiation.

Correlation Heatmap:

A heatmap illustrates the correlation between blood pressure, sugar levels, and weight.

How to Run

Execute the script using:

python script.py

Expected Output

Descriptive statistics of the dataset.

A pairplot showing relationships between health parameters.

A histogram of blood pressure distribution.

A scatter plot comparing sugar levels and weight.

A heatmap displaying correlations among the variables.

License

This project is for educational and exploratory purposes only. Feel free to modify and use it as needed.

Author

SHRISTI
