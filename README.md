# Employee Analysis

## Overview

This Jupyter notebook is designed to analyze various datasets from a call center. It processes employee data, handle time data, and productivity data to generate insights and visualizations. The primary tasks include data cleaning, transformation, and statistical analysis.

## Prerequisites

Before running the notebook, ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Required Python libraries (listed in the `requirements.txt` file)

## Installation

1. **Clone the repository**:
   ```sh
   git clone <repository_url>
   cd <repository_name>
   ```

2. **Create a virtual environment**:
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install the required libraries**:
   ```sh
   pip install -r requirements.txt
   ```

4. **Run Jupyter Notebook**:
   ```sh
   jupyter notebook
   ```

## Dataset

Place the following CSV files in the `data/` directory:

- `employee.csv`
- `employee_handle.csv`
- `employee_productivity.csv`

## Notebook Outline

1. **Import Necessary Libraries**:
   - Import libraries such as `pandas`, `ast`, `os`, `plotly.express` for data analysis and visualization.

2. **Load and Inspect Data**:
   - Load `employee.csv` into a DataFrame and inspect its structure and summary statistics.
   - Load `employee_handle.csv` with a custom delimiter and inspect its structure and summary statistics.
   - Load `employee_productivity.csv` and inspect its structure and summary statistics.

3. **Data Cleaning and Transformation**:
   - Convert seniority from years and months to total months.
   - Drop unnecessary columns and handle missing values.
   - Convert date columns to datetime format.
   - Create additional columns for further analysis.

4. **Descriptive Statistics**:
   - Generate descriptive statistics for relevant columns.
   - Visualize distributions and relationships using histograms and scatter plots.

5. **Correlation Analysis**:
   - Calculate and visualize correlation matrices for different datasets.

6. **Statistical Analysis and Visualization**:
   - Create box plots and scatter plots to analyze relationships between variables.
   - Generate heatmaps to visualize correlations.

## Usage

1. **Load and Inspect Data**:
   - The notebook loads and displays the first few rows of each dataset and provides summary statistics.

2. **Data Cleaning**:
   - Perform necessary data cleaning steps such as handling missing values, renaming columns, and converting data types.

3. **Visualization**:
   - Use various plots to visualize the data and understand relationships between variables.

4. **Statistical Analysis**:
   - Conduct correlation analysis and visualize the results using heatmaps.

## Conclusion

This project provides a comprehensive analysis of call center data, focusing on employee details, handle time, and productivity. The visualizations and statistical analyses help in understanding key patterns and relationships in the data.
