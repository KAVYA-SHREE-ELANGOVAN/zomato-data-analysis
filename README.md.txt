# Zomato Data Analysis Project

## 1. Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the Zomato restaurant dataset using Python.

The main objective is to explore restaurant data across different countries and cities, understand customer ratings, and analyse online delivery availability.

Through data cleaning, data manipulation, and visualisation, this project identifies useful patterns and insights from the dataset.

## 2. Problem Statement

The project aims to answer the following questions:

- Which countries have the highest number of restaurants?
- Which cities have the highest number of restaurants?
- How are restaurants distributed across different rating categories?
- How many restaurants provide online delivery?
- How do average restaurant ratings vary across countries?

## 3. Dataset Description

The project uses two CSV files:

- **ZOMATO_DATASET.csv** – Contains restaurant information such as restaurant names, locations, cuisines, average cost, ratings, votes, and online delivery availability.
- **country_codes.csv** – Contains country codes and their corresponding country names.

The two datasets are merged using the `country_code` column.

## 4. Data Cleaning and Preparation

The following data preparation steps were performed:

- Imported the required Python libraries.
- Loaded the datasets using Pandas.
- Inspected the dataset structure and information.
- Checked and handled missing values.
- Checked for duplicate records.
- Standardised column names.
- Checked and corrected data types where necessary.
- Merged the restaurant dataset with the country codes dataset.

## 5. Exploratory Data Analysis

The following analyses were performed:

### Country Analysis
Analysed restaurant distribution across countries and identified the countries with the highest restaurant counts.

### City Analysis
Identified cities with the highest number of restaurants.

### Rating Analysis
Examined restaurant rating categories and their distribution to understand customer ratings.

### Online Delivery Analysis
Analysed the availability of online delivery services among restaurants.

### Average Rating by Country
Compared average restaurant ratings across countries, excluding unrated restaurants.

## 6. Key Findings

- **Total Restaurants:** 9,551 restaurant records were analysed.
- **Top Country:** India has the highest number of restaurants, with 8,652 records.
- **Top City:** New Delhi has the highest number of restaurants, with 5,473 records.
- **Most Common Rating Category:** Average, with 3,737 restaurants.
- **Online Delivery:** 2,451 restaurants offer online delivery, while 7,100