Mortgage Loan Export Data Cleaning, Visualization, and Modeling
Overview
This Jupyter Notebook is designed to clean, preprocess, visualize, and model data from a mortgage loan dataset (LoanExport.csv). The notebook utilizes a custom module named data_cleaning_visualization and performs various data modeling techniques, with Logistic Regression yielding the best results.

Structure
The notebook is structured into several key sections:

Importing Libraries:

Essential Python libraries are imported, including Pandas, NumPy, Matplotlib, Seaborn, and the custom module data_cleaning_visualization.
Loading the Dataset:

The dataset LoanExport.csv is loaded into a Pandas DataFrame.
Data Exploration:

Basic data exploration is conducted to understand the structure and content of the dataset, including displaying the first few rows, checking data types, and summarizing the dataset.
Data Cleaning and Preprocessing:

Various data cleaning techniques are applied, such as handling missing values, removing duplicates, and transforming data types where necessary.
Visualization:

Visualizations are generated to explore and analyze the cleaned data, providing insights into key metrics and trends within the dataset.
Data Modeling:

Several machine learning models are applied to the processed data, including Logistic Regression, Decision Trees, and others.
Logistic Regression is highlighted as the model that provided the best results in terms of accuracy and other performance metrics.
How to Use
Requirements:

Ensure that you have the necessary Python libraries installed. You can install the required libraries using the following command:
bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn
Additionally, ensure that the custom module data_cleaning_visualization is available and correctly referenced within the notebook.
Running the Notebook:

Load the notebook in Jupyter or any compatible environment.
Follow the sequential execution of cells, starting from the top. Ensure that the dataset LoanExport.csv is in the correct directory or update the file path accordingly.
Customization:

You can modify the cleaning, visualization, and modeling steps to tailor the notebook to your specific needs.
Dependencies
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Custom Module: data_cleaning_visualization
Dataset
Filename: LoanExport.csv
Description: This dataset contains information on mortgage loans, including credit scores, payment dates, loan amounts, interest rates, and more.
Results
Best Model: Logistic Regression
Performance: The Logistic Regression model provided the highest accuracy and overall performance compared to other models.
