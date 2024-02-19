# Cleaning Data

This repository contains Python code to clean a dataset related to data science job postings. The dataset is copied for cleaning to preserve the original data. The cleaning process includes converting data types, specifically converting integer columns to int32, float columns to float16, and categorical columns to appropriate ordered or standard categories. 

Additionally, the code filters the dataset to include only entries where individuals have 10 or more years of experience at companies with at least 1000 employees.

## Usage

To use this code, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Python installed
3. Open and run the provided Python script `cleaning_data.ipynb`.
4. The cleaned dataset will be saved as `cleaned_dataset.csv` in the same directory.

## Dataset
(customer_train.csv)
The dataset used in this cleaning process contains information about data science job postings, including relevant experience, enrolled university, education level, experience, company size, and last new job. 

## Requirements

- Python 3.x
- Pandas
