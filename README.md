# Netflix-Data-Cleaning-and-Preprocessing-Using-Python
Exploratory analysis of the Netflix titles dataset using Python. This project focuses on data cleaning, missing-value analysis, preprocessing, and visualization to uncover insights about Netflix content, including movies, TV shows, genres, ratings, countries, and release trends.
# Netflix Data Cleaning and Preprocessing Using Python

##  Project Overview
This project focuses on cleaning, preprocessing, and exploring the Netflix Movies and TV Shows dataset using Python. It was developed as part of **Week 1 of the AI Pioneer Machine Learning Internship at Yuva Intern**.
The project demonstrates essential data preprocessing techniques, including missing value analysis, duplicate detection, data type conversion, categorical encoding, outlier detection, and normalization. Exploratory Data Analysis (EDA) is also performed to understand content distributions and identify patterns in the dataset.

##  Objectives
* Explore and understand a real-world dataset.
* Identify and handle missing values.
* Detect and remove duplicate records.
* Inspect and correct data types.
* Understand feature selection and categorical encoding.
* Detect potential outliers in numerical features.
* Apply Min-Max normalization to suitable numerical data.
* Perform EDA using statistical summaries and visualizations.
* Prepare a structured dataset for further analysis.

## 📂 Dataset

**Dataset:** Netflix Movies and TV Shows

**Source:** [Kaggle – Netflix Movies and TV Shows] (https://www.kaggle.com/datasets/shivamb/netflix-shows)

**Original dataset dimensions:**
* Rows: 8,807
* Columns: 12
The dataset contains information about Netflix movies and TV shows, including titles, directors, cast, countries, release years, ratings, durations, genres, and descriptions.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* VSCode

## Project Workflow

### 1. Data Loading and Exploration
* Import the required libraries.
* Load the dataset into a Pandas DataFrame.
* Inspect the first few records, dimensions, data types, and statistical summaries.
* 
### 2. Missing Value Analysis
* Identify missing values in each column.
* Examine the extent of missing data.
* Apply appropriate handling strategies based on the column characteristics.

### 3. Duplicate Detection
* Identify duplicate records.
* Remove duplicate rows where necessary.
* Verify the resulting dataset.

### 4. Data Type Conversion
* Inspect column data types.
* Convert date information into datetime format where appropriate.
* Handle invalid date values during conversion.

### 5. Feature Selection and Encoding
* Identify features relevant to the intended analysis.
* Explore categorical variables.
* Apply suitable encoding techniques to selected categorical features.

### 6. Outlier Detection
* Examine numerical features.
* Use boxplots to visualize potential outliers.
* Investigate unusual values before deciding whether they require treatment.

### 7. Normalization
* Apply Min-Max normalization to appropriate numerical features using Pandas.
* Verify the transformed values.

### 8. Exploratory Data Analysis
* Compare movies and TV shows.
* Analyze content distribution across release years.
* Visualize audience rating distributions.
* Explore content type patterns across release-year intervals.

## Visualizations

The project includes visual analysis such as:
* Movies vs. TV Shows distribution
* Netflix content by release year
* Content ratings distribution
* Movies and TV Shows by release year

## Results
The project provides a structured workflow for inspecting and preprocessing the Netflix dataset. It identifies missing data, examines duplicate records, transforms selected features, and generates visualizations to explore content patterns.
Final cleaning statistics and observations should be updated based on the executed notebook results.

## Learning Outcomes
* Gained practical experience with Pandas and NumPy.
* Understood missing value analysis and data cleaning.
* Practiced categorical encoding and numerical normalization.
* Learned to identify potential outliers.
* Developed data visualization skills using Matplotlib and Seaborn.
* Improved understanding of data preparation for machine learning.

SHAIK NIHASUHANI
AI Pioneer Machine Learning Intern
Yuva Intern
