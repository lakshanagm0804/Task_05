# Task 5: Exploratory Data Analysis (EDA) – Titanic Dataset

## 📌 Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The analysis aims to uncover patterns, relationships, trends, and anomalies through statistical summaries and data visualizations.

## 🛠️ Tools & Libraries Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📂 Dataset

* **Dataset Name:** Titanic Dataset (`train.csv`)
* **Source:** Kaggle Titanic Survival Prediction Dataset

## 📋 Steps Performed

### 1. Data Loading

* Imported the dataset using Pandas.
* Displayed the first few records to understand the structure.

### 2. Data Cleaning

* Checked dataset information using `.info()`.
* Identified missing values using `.isnull().sum()`.
* Filled missing values in the `Age` column using the median.
* Filled missing values in the `Embarked` column using the mode.
* Dropped the `Cabin` column due to a large number of missing values.
* Converted the `Age` column from `float64` to `int64`.

### 3. Statistical Exploration

* Used `.describe()` to generate summary statistics.
* Used `.value_counts()` to analyze categorical variables such as:

  * Survived
  * Sex
  * Pclass
  * Embarked

### 4. Data Visualization

The following visualizations were created:

* Histograms
* Boxplots
* Scatterplots
* Pairplot
* Correlation Heatmap

### 5. Key Insights

* Most passengers were between 20 and 40 years old.
* The majority of passengers traveled in third class.
* Male passengers outnumbered female passengers.
* Female passengers had a significantly higher survival rate.
* First-class passengers had better survival chances than third-class passengers.
* The Fare column contains several outliers.
* Passenger class and fare show a moderate negative correlation.

## 📊 Outcome

This project helped in understanding how Exploratory Data Analysis can be used to identify patterns, trends, relationships, and anomalies in real-world datasets. The insights obtained from the analysis can be useful for further predictive modeling and machine learning tasks.

## 📁 Deliverables

* `Task5_EDA.ipynb`
* `Task5_Titanic_EDA_Report.pdf`
* `README.md`
