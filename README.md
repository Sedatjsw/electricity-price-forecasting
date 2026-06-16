# Electricity Price Forecasting & Energy Market Analysis

This project explores electricity price forecasting and energy market analysis using machine learning, big data processing, and time-based analytics techniques applied to the Turkish electricity market.

The project combines exploratory data analysis (EDA), feature engineering, distributed data processing, and predictive modelling using Apache Spark and Databricks.

The main objective of the project is to analyse electricity market behaviour and develop machine learning models capable of forecasting electricity prices using electricity consumption, generation sources, and temporal variables.

---

## Project Overview

Electricity markets are highly dynamic systems where demand and prices fluctuate continuously due to multiple interacting factors.

This project investigates:

* Electricity consumption behaviour
* Electricity price fluctuations
* Relationships between demand, generation, and pricing
* Seasonal and intraday market patterns
* Machine learning-based electricity price forecasting

The analysis was performed using real-world hourly electricity market data collected between 2018 and 2023.

The project focuses on building a complete analytical workflow using both traditional data analysis techniques and scalable big data technologies.

---

## Technologies Used

* Python
* Databricks
* Apache Spark (PySpark)
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Dataset Features

The dataset contains hourly electricity market information, including:

* Electricity consumption
* Total electricity generation
* Natural gas generation
* Imported coal generation
* Wind generation
* Solar generation
* Electricity prices
* Timestamp information

Additional time-based variables were engineered during preprocessing, including:

* Hour of day
* Day of week
* Month
* Weekend indicator

---

## Data Processing Pipeline

### Data Loading & Processing

* Processed large-scale electricity market data using Apache Spark and Databricks

### Data Cleaning

* Missing value analysis
* Duplicate detection
* Data type validation
* Verification of abnormal values

### Exploratory Data Analysis (EDA)

* Electricity consumption trend analysis
* Price distribution analysis
* Correlation analysis between variables
* Intraday demand pattern analysis
* Seasonal electricity consumption analysis

### Feature Engineering

* Time-based feature extraction
* Preparation of machine learning input features

### Machine Learning Models

The following regression models were implemented:

* Linear Regression
* Random Forest Regression

### Model Evaluation

Models were evaluated using:

* RMSE (Root Mean Squared Error)
* R² Score

Feature importance analysis was also performed to identify the most influential predictors of electricity prices.

---

## Key Findings

* Electricity prices are strongly influenced by hourly demand fluctuations
* Time-based features significantly improve forecasting performance
* Random Forest Regression substantially outperformed Linear Regression
* Electricity market behaviour exhibits strong nonlinear relationships
* Imported coal generation, solar generation, and electricity consumption were among the most influential variables affecting price prediction

---

## Technical Report

A detailed technical report containing:

* Exploratory Data Analysis
* Correlation Analysis
* Model Evaluation
* Actual vs Predicted Analysis
* Feature Importance Analysis
* Forecasting Results

is included in the `reports` folder.

---

## Project Structure

```text
electricity-price-forecasting
 ├── data
 ├── notebooks
 ├── reports
 └── README.md
```

---

## Skills Demonstrated

* Data Analysis
* Machine Learning
* Forecasting
* Big Data Processing
* Apache Spark
* Databricks
* Regression Modeling
* Exploratory Data Analysis
* Feature Engineering
* Data Visualisation
* Time-Series Style Analysis

---

## Conclusion

This project demonstrates how machine learning and big data technologies can be applied to real-world electricity market forecasting problems.

The integration of Databricks, Apache Spark, exploratory data analysis, and predictive modelling provides a scalable workflow for analysing high-frequency electricity market data.

The project also highlights the importance of nonlinear machine learning methods when modelling complex energy market behaviour.

---

## Author

Sedat Aydin
MSc Big Data Analytics & Artificial Intelligence
