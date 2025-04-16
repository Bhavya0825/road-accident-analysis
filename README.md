# 🚗 Road Accident Analysis in India

This project delves into the patterns, causes, and severity of road accidents in India using comprehensive datasets. It encompasses data preprocessing, exploratory data analysis (EDA), and machine learning modeling to predict accident severity.

## 📁 Dataset

The primary dataset utilized in this project is sourced from Kaggle:

- **AccidentsBig.csv**: Contains detailed records of road traffic accidents, including features like location, time, day of the week, number of vehicles involved, casualties, and more.

> 📌 Dataset Source: [Road Accident Severity in India - Kaggle](https://www.kaggle.com/datasets/s3programmer/road-accident-severity-in-india)

## 🔍 Exploratory Data Analysis (EDA)

The EDA section provides insights into the dataset through:

- **Distribution Analysis**: Examining the frequency of accidents across different days, weather conditions, and road types.
- **Severity Assessment**: Analyzing the distribution of accident severity levels.
- **Correlation Studies**: Investigating relationships between numerical features such as the number of vehicles involved and casualties.

Visualizations include histograms, count plots, and heatmaps to facilitate a comprehensive understanding of the data.

## 🧠 Machine Learning Model: Predicting Accident Severity

A **Random Forest Classifier** is employed to predict the severity of accidents based on selected features.

### ✅ Features Used:

- Number of Vehicles Involved
- Number of Casualties
- Day of the Week
- Weather Conditions
- Road Type

### 🎯 Target Variable:

- **Accident Severity**: Categorized into different levels indicating the severity of accidents.

### 🛠️ Model Workflow:

1. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical variables using Label Encoding.

2. **Model Training**:
   - Splitting the dataset into training and testing sets.
   - Training the Random Forest Classifier on the training data.

3. **Evaluation**:
   - Assessing model performance using accuracy score and classification report.

## 📊 Tools & Libraries

- **Pandas**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning modeling and evaluation.
- **Google Colab**: Interactive development environment.

