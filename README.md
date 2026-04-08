# Flight Price Analysis & Feature Engineering

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) and Feature Engineering on a flight price dataset to identify key factors influencing ticket prices.

## Objectives
- Analyze flight pricing patterns
- Perform data cleaning and preprocessing
- Extract meaningful features from raw data
- Prepare dataset for machine learning models

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Dataset Features
- Airline
- Source & Destination
- Date of Journey
- Departure & Arrival Time
- Duration
- Total Stops
- Additional Info
- Price (Target Variable)

## Steps Performed

### 1. Data Cleaning
- Removed unnecessary columns (Route, Date_of_Journey, etc.)
- Handled missing values
- Converted data types

### 2. Feature Engineering
- Extracted Date, Month, Year from journey date
- Extracted hour and minute from departure and arrival time
- Converted duration into usable format

### 3. Data Transformation
- Converted categorical variables into numerical format
- Applied One Hot Encoding using Scikit-learn

## Key Insights
- Flights with more stops tend to have lower prices
- Certain airlines consistently have higher fares
- Ticket prices vary significantly based on month and demand
- Departure time impacts pricing trends

## Business Impact
This analysis can help:
- Airlines optimize pricing strategies
- Customers identify cheaper travel options
- Businesses understand demand patterns

## How to Run

1. Clone the repository:
   git clone <your-repo-link>

2. Install dependencies:
   pip install -r requirements.txt

3. Run Jupyter Notebook:
   jupyter notebook


## 📎 Dataset Source
Kaggle - Flight Price Prediction Dataset
