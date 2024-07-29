# Heart Disease Data Analysis

This project aims to perform exploratory data analysis (EDA) on a heart disease dataset and visualize the relationships between different attributes and the presence of heart disease.

## Dataset

The dataset contains various attributes related to heart disease, such as age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, the slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, thalassemia, and the target variable indicating the presence of heart disease.

## Prerequisites

Make sure you have the following Python libraries installed:

- pandas
- matplotlib
- seaborn

You can install these libraries using pip:

```bash
pip install pandas matplotlib seaborn
```

## Usage
- Clone the repository or download the script and the dataset.
- Place the dataset (CSV file) in the same directory as the script.
- Update the file path in the script to point to the dataset:

```bash
file_path = 'path/to/your/Heart Disease data.csv'
```
## Run the script:
```bash
python Diagnostic analysis.py
```
## Script Overview
The script performs the following steps:

- Load the data: Reads the dataset from the CSV file.
- Display the first few rows of the data: Prints the first few rows to understand the structure of the dataset.
- Generate distributions for various attributes: Creates histograms and count plots for attributes like age, sex, chest pain type, resting blood pressure, serum cholesterol, maximum heart rate achieved, exercise-induced angina, number of major vessels colored by fluoroscopy, and thalassemia.
- Create a correlation matrix heatmap: Displays a heatmap of the correlation matrix to understand the relationships between different attributes.
- Visualize the relationships between key attributes and the presence of heart disease: Generates plots to show how attributes like age, chest pain type, serum cholesterol, maximum heart rate achieved, exercise-induced angina, and the number of major vessels colored by fluoroscopy relate to the presence of heart disease.
## Visualizations
The script produces the following visualizations:

- Age Distribution: Histogram showing the distribution of ages.
- Sex Distribution: Count plot showing the distribution of sexes.
- Chest Pain Type Distribution: Count plot showing the distribution of chest pain types.
- Resting Blood Pressure Distribution: Histogram showing the distribution of resting blood pressure.
- Serum Cholesterol Distribution: Histogram showing the distribution of serum cholesterol.
- Maximum Heart Rate Achieved Distribution: Histogram showing the distribution of maximum heart rate achieved.
- Exercise-Induced Angina Distribution: Count plot showing the distribution of exercise-induced angina.
- Major Vessels Colored by Fluoroscopy Distribution: Count plot showing the distribution of major vessels colored by fluoroscopy.
- Thalassemia Distribution: Count plot showing the distribution of thalassemia.
- Correlation Matrix: Heatmap showing the correlation matrix of the attributes.
- Age Distribution by Heart Disease Presence: Histogram showing the age distribution based on the presence of heart disease.
- Chest Pain Type Distribution by Heart Disease Presence: Count plot showing the chest pain type distribution based on the presence of heart disease.
- Serum Cholesterol Distribution by Heart Disease Presence: Histogram showing the serum cholesterol distribution based on the presence of heart disease.
- Maximum Heart Rate Achieved by Heart Disease Presence: Histogram showing the maximum heart rate achieved based on the presence of heart disease.
- Exercise-Induced Angina by Heart Disease Presence: Count plot showing the exercise-induced angina distribution based on the presence of heart disease.
- Major Vessels Colored by Fluoroscopy by Heart Disease Presence: Count plot showing the distribution of major vessels colored by fluoroscopy based on the presence of heart disease.
## Conclusion
This script provides an initial exploratory data analysis of the heart disease dataset, helping to understand the distribution of attributes and their relationships with the presence of heart disease. Further analysis can be performed to build predictive models or derive more insights from the data.
