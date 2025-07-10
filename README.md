# Banking-Domain
# Banking Data Exploratory Data Analysis (EDA)

## Project Objective
To explore and analyze a banking dataset using Python libraries like Pandas, Seaborn, and Matplotlib. The goal is to uncover customer trends, income bands, account distributions, and risk insights.

## Dataset Description
- Contains banking-related information such as:
  - Estimated income
  - Loans
  - Deposits
  - Credit card balances
  - Customer properties, nationalities, and more
- Includes both categorical and numerical fields

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key EDA Tasks Performed
- Loaded dataset and checked info, shape, and description
- Created `Income Band` column based on Estimated Income
- Performed value counts and plotted countplots for all categorical columns
- Visualized distributions for numerical columns using histograms
- Created a correlation heatmap for numerical features

## Visualizations
- Count plots for categorical features
- Histograms for numerical variables
- Correlation matrix heatmap for understanding relationships

## Future Improvements
- Add interactive dashboard using Power BI or Tableau
- Apply feature engineering for model building
- Train ML model for predicting loan default risk (if labels are available)

## How to Run
1. Clone the repository
2. Open `banking_eda.ipynb` in Jupyter Notebook or Google Colab
3. Install required packages:
   ```bash
   pip install pandas matplotlib seaborn numpy
