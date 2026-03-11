![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit Learn](https://img.shields.io/badge/ScikitLearn-ML-orange)
![License](https://img.shields.io/badge/License-MIT-red)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)

# India Startup Layoffs Analysis and Prediction

## Project Overview

This project analyzes global layoff data and focuses on layoffs occurring in Indian companies. The goal is to understand patterns in layoffs across industries, companies, and time periods, and explore whether factors like funding or company stage influence layoffs.

The project includes both **Exploratory Data Analysis (EDA)** and **machine learning regression models** to explore potential predictions related to layoffs.

---

## Objectives

* Analyze layoff trends in Indian startups and companies
* Identify industries and companies with the highest layoffs
* Understand how funding and company stage relate to layoffs
* Visualize layoff patterns over time
* Build regression models to explore potential layoff predictions

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Dataset Description

The dataset contains records of layoffs from companies worldwide with attributes such as:

* Company Name
* Industry
* Total Employees Laid Off
* Percentage of Layoffs
* Date of Layoff
* Country
* Funding Raised
* Company Stage

For this project, the dataset is filtered to analyze **layoffs occurring in India**.

---

## Project Workflow

### 1. Data Collection

The layoff dataset is loaded and inspected for structure and missing values.

### 2. Data Cleaning

* Removed unnecessary columns
* Handled missing values
* Converted date fields into proper format
* Converted numeric columns for analysis

### 3. Exploratory Data Analysis

Key insights explored include:

* Layoffs by company
* Layoffs by industry
* Layoffs by time period
* Layoff distribution across sectors

### 4. Data Visualization

Visualizations were created to better understand patterns in layoffs using bar charts and trend graphs.

### 5. Regression-Based Prediction

Machine learning regression models are applied to explore potential relationships between:

* Funding raised
* Industry
* Company stage
* Layoff numbers

These models attempt to estimate layoffs based on available features.

---

## Project Structure

india-company-layoffs-analysis
│
├── layoffs.ipynb
├── layoffs.csv
├── README.md
├── requirements.txt

---

## How to Run the Project

### 1. Clone the Repository

git clone https://github.com/yourusername/india-company-layoffs-analysis.git

### 2. Navigate to the Project Folder

cd india-company-layoffs-analysis

### 3. Install Dependencies

pip install -r requirements.txt

### 4. Run the Notebook

Open the notebook using Jupyter Notebook or VS Code.

---

## Future Improvements

* Build advanced predictive models for layoffs
* Create an interactive dashboard using Streamlit or Power BI
* Perform deeper analysis on startup funding and layoffs
* Deploy the project as a web-based analytics tool

---

## Authors

Dheerendra Pratap Singh
Himanvi Damarla

