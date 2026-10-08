# Titanic Dataset — Exploratory Data Analysis

An Exploratory Data Analysis (EDA) project on the Titanic dataset using Python to understand passenger characteristics, data quality, and factors associated with survival.

## Project Overview

This project analyzes the Titanic passenger dataset to identify patterns and relationships between passenger characteristics and survival outcomes.

The analysis focuses on:

* Understanding the structure and characteristics of the dataset
* Identifying missing values and duplicate records
* Cleaning and preparing the data for analysis
* Studying passenger demographics and distributions
* Analyzing survival based on gender and passenger class
* Exploring the relationship between fare, age, passenger class, and survival
* Deriving meaningful insights from visual and statistical analysis

## Dataset

The project uses the Titanic dataset containing **891 passenger records and 12 original columns**.

Important features include:

| Feature     | Description                       |
| ----------- | --------------------------------- |
| PassengerId | Unique passenger identifier       |
| Survived    | Survival status (0 = No, 1 = Yes) |
| Pclass      | Passenger class (1, 2, 3)         |
| Name        | Passenger name                    |
| Sex         | Passenger gender                  |
| Age         | Passenger age                     |
| SibSp       | Number of siblings/spouses aboard |
| Parch       | Number of parents/children aboard |
| Ticket      | Ticket number                     |
| Fare        | Passenger fare                    |
| Cabin       | Cabin information                 |
| Embarked    | Port of embarkation               |

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Jupyter Notebook
* Git & GitHub

## EDA Workflow

### 1. Data Inspection

* Dataset shape and structure
* Column names and data types
* Initial data samples
* Descriptive statistics

### 2. Data Quality Analysis

* Missing-value analysis
* Duplicate-value checking
* Identification of incomplete features
* Categorical value inspection

### 3. Data Cleaning

* Missing `Age` values handled using the median
* Missing `Embarked` values handled using the mode
* `Cabin` availability represented using a `CabinKnown` feature
* Original `Cabin` column removed due to extensive missing data
* Duplicate records checked and verified

### 4. Exploratory Analysis

The project includes analysis of:

* Overall survival distribution
* Passenger class distribution
* Gender distribution
* Age distribution
* Fare distribution
* Survival by gender
* Survival by passenger class
* Fare distribution across passenger classes
* Fare distribution by survival
* Survival based on gender and passenger class
* Correlation between numerical variables

## Key Findings

* The overall survival rate was approximately **38.38%**.
* Female passengers had a substantially higher survival rate than male passengers.
* Passenger class showed a strong relationship with survival, with higher-class passengers generally having better survival outcomes.
* Fares were generally higher among passengers in higher passenger classes.
* Fare distributions differed between passengers who survived and those who did not.
* Age showed differences between survivors and non-survivors, suggesting that age may have influenced survival outcomes.
* Gender and passenger class together provided a clearer view of differences in survival rates.

## Project Structure

```text
Minor_project_1_UNLOX/
│
├── Minor_1.ipynb
├── EDA_Minor_Project_Report.pdf
└── README.md
```

## Conclusion

The analysis shows that passenger survival on the Titanic was not evenly distributed. Gender and passenger class were particularly important factors associated with survival, while age and fare also showed meaningful patterns.

This project demonstrates the use of Python-based Exploratory Data Analysis to inspect, clean, visualize, and interpret real-world tabular data.

## Author

**Thashan Sai Modewar**
AI & Data Science Student
VNR Vignana Jyothi Institute of Engineering & Technology

## Repository

This repository contains the complete notebook and project report for the Titanic EDA Minor Project.
