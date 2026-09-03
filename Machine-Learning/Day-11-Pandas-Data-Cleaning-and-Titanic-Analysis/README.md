# Day 11 - Pandas Data Cleaning and Titanic Analysis

This folder contains my Day 11 practical work on Pandas and data cleaning from the Data and Business Analysis with AI program.

## Topics Covered

### Data Cleaning

- Finding duplicate records
- `duplicated()`
- `drop_duplicates()`
- Adding new columns
- Removing columns
- `axis=0` and `axis=1`
- Checking missing values
- `isnull()`
- Counting missing values using `sum()`

### Missing Value Handling

- `mode()`
- `mean()`
- `median()`
- `fillna()`
- Filling categorical values
- Filling numerical values
- Handling missing values in datasets

### Data Analysis

- `groupby()`
- Aggregation using `agg()`
- `max()`
- `mean()`
- `value_counts()`
- Group-based analysis
- Multiple conditions

### Titanic Dataset

- Loading a CSV dataset using `read_csv()`
- Exploring the Titanic dataset
- Checking dataset information
- Checking duplicates
- Checking missing values
- Handling missing Age values
- Handling missing Cabin values
- Handling missing Embarked values
- Dropping unnecessary columns
- Renaming columns
- Analyzing Gender
- Analyzing Survival
- Analyzing Passenger Class
- Grouping Survival and Gender
- Grouping Survival and Passenger Class
- Using `lambda` with `apply()`
- Converting Survival values into `Alive` and `Dead`

### Visualization

- Introduction to Histogram
- Plotting Age distribution using Matplotlib

## Practical Work

The notebook contains practical examples of Pandas data cleaning and analysis using a sample student DataFrame and the Titanic dataset.

## Tool Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib

## Dataset

The Day 11 practical work uses the Titanic dataset in two forms:

- `Titanic-Dataset-Unclean.csv` - Original dataset containing missing values and the original columns.
- `Titanic-Dataset-Clean.csv` - Cleaned dataset after applying data-cleaning operations.

## Data Cleaning Tasks

- Identifying missing values
- Handling missing values
- Removing unnecessary columns
- Renaming columns
- Working with cleaned categorical and numerical data


## Learning Objective

To understand practical data cleaning techniques in Pandas and apply them to a real-world dataset. The Titanic dataset is used to practice missing-value handling, duplicate removal, column manipulation, grouping, aggregation, and basic data visualization.

## Notebook

[Day-11-Pandas-Data-Cleaning-and-Titanic-Analysis.ipynb](Day-11-Pandas-Data-Cleaning-and-Titanic-Analysis.ipynb)
