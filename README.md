# Car Market Trends Analysis

## Data Analytics Project Using CarDekho Used-Car Dataset

This project analyzes used-car market trends using the CarDekho dataset. The analysis focuses on factors influencing used-car selling prices, depreciation, car age, mileage, fuel type, transmission, seller type, ownership, and brand.

## Project Objective

* Analyze factors affecting used-car selling prices
* Study depreciation patterns
* Analyze car age and mileage
* Compare fuel types
* Compare manual and automatic cars
* Analyze seller and ownership categories
* Compare brands based on average selling price
* Generate business insights and recommendations

## Dataset

The project uses a CarDekho used-car dataset containing information about:

* Car Name
* Manufacturing Year
* Selling Price
* Present Price
* Kilometers Driven
* Fuel Type
* Seller Type
* Transmission
* Owner

## Data Cleaning

The project includes:

* Missing-value checking
* Duplicate detection
* Duplicate removal
* Data-type validation
* Feature engineering

The original dataset contains 301 records. After removing 2 duplicate records, 299 records are used for analysis.

# Feature Engineering

# Car Age
Car Age = 2020 - Year

# Depreciation

Depreciation = Present Price - Selling Price


# Depreciation Percentage

Depreciation % =((Present Price - Selling Price) / Present Price) × 100


# Key Results

| Metric                         | Result |
| ------------------------------ | -----: |
| Cars analyzed                  |    299 |
| Average Selling Price          |   4.59 |
| Highest Selling Price          |  35.00 |
| Average Depreciation           | 36.62% |
| Present Price vs Selling Price |  0.876 |
| Car Age vs Selling Price       | -0.234 |
| Kms Driven vs Selling Price    |  0.029 |

## Key Insights

* Present Price has a strong positive relationship with Selling Price.
* Car Age has a negative relationship with Selling Price.
* Kilometers Driven has a very weak linear relationship with Selling Price in this dataset.
* Diesel vehicles have the highest average selling price among fuel categories.
* Automatic vehicles have the highest average selling price among transmission categories.
* Average depreciation is approximately 36.62%.

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

# Project Workflow

Dataset
   ↓
Data Cleaning
   ↓
Feature Engineering
   ↓
Exploratory Data Analysis
   ↓
Statistical Analysis
   ↓
Visualization
   ↓
Insights
   ↓
Recommendations
   ↓
Conclusion


#Future Scope

* Build an interactive Power BI dashboard
* Develop a machine-learning model for price prediction
* Add newer market data
* Perform deeper outlier analysis
* Analyze pricing trends over time

# Author
Pujari Suraksha Shankar

Data Analytics Project
Car Market Trends Analysis
