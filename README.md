# Flight Operations Data Analysis

A complete data analysis notebook using Python and Pandas to explore and analyze flight operations data.

## Overview

This project presents a complete data analysis workflow performed on a Flight Operations dataset using Python and Pandas.

The analysis focuses on understanding flight operations, passenger activity, delays, airlines, routes, ticket prices, weather conditions, booking channels, and passenger satisfaction.

This project was created as part of my **Day 10 Python Programming Internship Assignment**.

---

## Analysis Performed

The notebook covers the following data analysis operations:

- Loading the Flight Operations dataset
- Inspecting the dataset structure
- Checking the number of rows and columns
- Examining column names and data types
- Viewing the first and last records
- Viewing random samples
- Generating descriptive statistics
- Checking missing values
- Checking duplicate records
- Selecting relevant columns
- Filtering flight records
- Sorting data based on different attributes
- Grouping and aggregating data using `groupby()`
- Analyzing airlines
- Analyzing origins and destinations
- Analyzing flight statuses
- Analyzing travel classes
- Analyzing weather conditions
- Analyzing booking channels
- Calculating passenger and delay statistics
- Comparing passenger satisfaction
- Identifying operational patterns and key findings
- Writing evidence-based observations

---

## Key Findings

The analysis identified several important characteristics of the dataset:

- The dataset contains **180 flight records** and **17 features**.
- A total of **22,099 passengers** are recorded across the flights.
- The average delay is approximately **19.34 minutes**.
- The maximum recorded delay is **110 minutes**.
- The average ticket price is approximately **₹6,111.68**.
- The average passenger satisfaction score is approximately **3.49 out of 5**.
- The dataset contains **114 on-time flights, 59 delayed flights, and 7 cancelled flights**.
- Differences in delays, passenger volume, weather conditions, and satisfaction can be observed across the dataset.

---

## Technologies Used

- Python 3
- Pandas
- NumPy
- Google Colab
- Jupyter Notebook

---

## Pandas Concepts Demonstrated

The notebook demonstrates several important Pandas concepts, including:

```text
DataFrame creation and loading
head()
tail()
sample()
shape
columns
dtypes
info()
describe()
isnull()
duplicated()
Column selection
Boolean filtering
sort_values()
groupby()
Aggregation functions
DateTime operations
