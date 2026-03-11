# Housing Dataset - Exploratory Data Analysis

## Team Members

- Marek Olejniczak - [GitHub](https://github.com/marek-olejniczak)
- Tomasz Preś - [GitHub](https://github.com/tomasz-pres)
- Michał Pokładowski - [GitHub](https://github.com/michaelo-ponteski)

## Project Overview

This project performs a comprehensive exploratory data analysis (EDA) on a housing dataset to understand the relationships between various features and housing prices. The analysis includes data quality checks, univariate and multivariate analysis, and statistical testing.

## Dataset

The dataset is stored in `Housing.csv` and contains information about housing properties including:

- **Numerical features**: price, area, number of bedrooms, bathrooms, stories, parking spaces
- **Categorical features**: main road access, guest room, basement, hot water heating, air conditioning, preferred area, furnishing status

## Analysis Structure

### 1. Data Loading and Overview

- Load the housing dataset
- Examine dataset shape, columns, and data types
- Generate descriptive statistics for numerical features

### 2. Data Quality Checks

- **Missing values**: Check for any null values in the dataset
- **Duplicate rows**: Identify duplicate entries

### 3. Univariate Analysis

#### Numerical Features

- Distribution analysis using histograms
- Boxplots to identify outliers
- Pairplot visualization to explore relationships between numerical features

#### Categorical Features

- Count plots for each categorical variable
- Frequency distribution visualization

### 4. Correlation Analysis

- Compute correlation matrix for numerical features
- Identify features most correlated with price
- Visualize correlation matrix using heatmap

### 5. Key Findings

- **Area** and **bathrooms** are the two most correlated features with price
- Price vs Area shows a strong positive linear relationship
- Furnishing status, preferred area, and other amenities impact housing prices
- All features show some level of influence on the final price

### 6. Multivariate Analysis

- Price distribution across different categorical features
- 3D scatter plot combining area, furnishing status, and price with preferred area coloring
- Chi-square test to identify significant relationships between categorical features

## Requirements

```python
pandas
numpy
matplotlib
seaborn
scipy
```

## Usage

1. Ensure `Housing.csv` is in the same directory as the notebook
2. Open `housing.ipynb` in Jupyter Notebook or VS Code
3. Run all cells sequentially to reproduce the analysis

## Files in Repository

- `housing.ipynb` - Main analysis notebook
- `Housing.csv` - Housing dataset
- `EDA.ipynb` - Additional EDA notebook
- `README.md` - This file

## Visualizations

The analysis includes multiple types of visualizations:

- Histograms for distribution analysis
- Box plots for outlier detection
- Pair plots for feature relationships
- Correlation heatmap
- Count plots for categorical features
- Regression plots for continuous relationships
- 3D scatter plots for multivariate exploration
- Cross-tabulation heatmaps for categorical relationships

## Key Insights

1. Area is the strongest predictor of house price
2. Number of bathrooms significantly correlates with price
3. Preferred area location impacts pricing
4. Furnishing status affects property values
5. All categorical features show statistical significance in relation to house prices
