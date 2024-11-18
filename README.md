# Titanic-Dataset-Analysis-and-Visualization
This project performs a detailed analysis of the Titanic dataset using Python. It covers various aspects such as data cleaning, exploration, visualization, and basic statistical analysis.


Titanic Dataset Analysis and Visualization
This repository contains a comprehensive analysis of the Titanic dataset using Python. The project involves data cleaning, exploration, visualization, and statistical analysis to gain insights into survival rates, demographic patterns, and relationships between various features of the passengers.

Project Overview
In this project, we perform the following tasks:

Data Loading & Cleaning: Importing the dataset, handling missing values, and removing duplicate rows.
Feature Engineering: Extracting useful features, such as passenger titles (e.g., Mr., Mrs.), and calculating family sizes.
Data Visualization: Visualizing the distribution of variables like age, fare, survival rates, and demographics using Matplotlib and Seaborn.
Statistical Analysis: Analyzing the correlation between numerical variables and survival rates, as well as calculating the central tendency (mean, median, mode) and spread (standard deviation, interquartile range).
Survival Analysis: Investigating survival rates based on sex, passenger class, and other features.
Libraries Used
Pandas: For data manipulation and cleaning.
NumPy: For numerical operations.
Matplotlib: For creating visualizations.
Seaborn: For advanced data visualization and statistical plotting.
Scikit-learn: For machine learning utilities (optional if building models).
Installation
To run this project, you need to have Python installed along with the necessary libraries. Follow these steps to get started:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/titanic-dataset-analysis.git
cd titanic-dataset-analysis
Install required libraries:

bash
Copy code
pip install -r requirements.txt
Download the Titanic dataset (Titanic-Dataset.csv) and place it in the project folder.

Run the analysis:

bash
Copy code
python titanic_analysis.py
Files in this Repository
titanic_analysis.py: The main Python script that performs the analysis and visualization.
Titanic-Dataset.csv: The raw Titanic dataset.
requirements.txt: The list of required Python libraries for the project.
README.md: This file.
Project Insights
1. Demographic Distribution:
Visualized the distribution of passengers' ages, fares, and survival status.
Explored survival rates based on passenger sex and class.
2. Correlation Analysis:
Computed and visualized the correlation between numerical variables, identifying key relationships (e.g., Fare and Pclass).
3. Survival Analysis:
Survival rates were analyzed based on passenger class, sex, and other demographic factors.
The project uncovered insights like how the survival rate was higher for women and 1st-class passengers.
Contributing
Feel free to fork the repository and contribute by opening pull requests. If you have any suggestions or improvements, feel free to submit issues or pull requests.
