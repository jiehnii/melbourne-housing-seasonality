# Melbourne Housing Seasonality Analysis

This project explores how **Melbourne housing prices** vary across different times of the year.

The analysis focuses on:
- How average prices change by **month**
- Differences between **seasons** (Summer, Autumn, Winter, Spring)
- Whether **weekend vs weekday** sales show price differences
- Fitting a simple **polynomial regression** to capture the seasonal pattern

## Files in this repository

- `melbourne_housing_seasonality.ipynb`  
  Jupyter Notebook containing the full analysis, code, and visualisations.

- `melb_housing_data.csv`  
  Melbourne housing dataset used in the notebook.

## Tech stack

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## How to run the notebook

1. Clone or download this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Open the notebook:
   jupyter notebook "Melbourne Housing Problem Description.ipynb"
4. Run the cells from top to bottom.

   ```bash
   pip install -r requirements.txt

## Main insights
- Prices tend to be lower around mid–year (e.g. Winter months).
- Prices are higher at the start and end of the year, especially around December.
- Weekend sales can show slightly higher prices, likely due to auctions and increased competition.
- A simple quadratic regression captures a U-shaped pattern over the months.

## Possible future improvements
- Include more features (suburb, property type, rooms) in a multivariate model.
- Build predictive models for price (e.g. regression or tree-based models).
- Extend the analysis to multiple years or other Australian cities.
