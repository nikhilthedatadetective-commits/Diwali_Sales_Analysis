# Diwali Sales Data Analysis

A comprehensive exploratory data analysis (EDA) project examining Diwali sales patterns to identify customer demographics, purchasing behaviors, and product preferences.

## Overview

This project analyzes sales data from a Diwali festival campaign to uncover insights about customer segments and their buying patterns. The analysis helps understand which demographic groups are the most valuable customers and what products they prefer.

## Dataset

- **File**: `Diwali Sales Data.csv`
- **Total Records**: 11,251 entries
- **Features**: 15 columns (13 after cleaning)

### Key Columns
- `User_ID`: Unique customer identifier
- `Gender`: Customer gender
- `Age Group`: Categorized age ranges
- `Marital_Status`: Marriage status (0 or 1)
- `State`: Customer's state
- `Zone`: Geographic zone
- `Occupation`: Customer's profession
- `Product_Category`: Type of product purchased
- `Orders`: Number of orders placed
- `Amount`: Purchase amount

## Technologies Used

- **Python 3.x**
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computations
- **matplotlib**: Data visualization
- **seaborn**: Statistical data visualization

## Installation

```bash
pip install numpy pandas matplotlib seaborn
```

## Data Cleaning Steps

1. Removed irrelevant columns (`Status`, `unnamed1`)
2. Dropped null values from the dataset
3. Converted `Amount` column to integer type
4. Final dataset: 11,239 records with 13 features

## Analysis Performed

### 1. Gender Analysis
- Distribution of buyers by gender
- Total sales amount by gender
- **Finding**: Females are the majority buyers with higher purchasing power

### 2. Age Group Analysis
- Customer distribution across age groups
- Sales amount by age group and gender
- **Finding**: 26-35 age group (especially females) are the primary buyers

### 3. Geographic Analysis
- Top 10 states by order volume
- Top 10 states by sales amount
- **Finding**: Uttar Pradesh, Maharashtra, and Karnataka lead in orders and revenue

### 4. Marital Status Analysis
- Buyer distribution by marital status
- Sales amount by marital status and gender
- **Finding**: Married women show the highest purchasing power

### 5. Occupation Analysis
- Customer distribution across occupations
- Sales amount by occupation
- **Finding**: IT, Healthcare, and Aviation professionals are top buyers

### 6. Product Category Analysis
- Most popular product categories
- Top 10 products by orders
- **Finding**: Food, Clothing, and Electronics are the bestselling categories

## Key Insights

### Target Customer Profile
**Married women aged 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation sectors are the most likely to purchase products from Food, Clothing, and Electronics categories.**

## Visualizations

The project includes multiple visualizations:
- Count plots for demographic distributions
- Bar charts for sales comparisons
- Grouped bar charts for cross-category analysis

## Usage

1. Place `Diwali Sales Data.csv` in the project directory
2. Run the Jupyter notebook or Python script
3. View generated visualizations and insights

## Future Improvements

- Time-series analysis of sales trends
- Customer segmentation using clustering
- Predictive modeling for sales forecasting
- ROI analysis for marketing campaigns

