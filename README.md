# Retail-Sales-Prediction
Developed a predictive analytics pipeline to identify key drivers of product sales and evaluate model performance across Random Forest and Gradient Boosting algorithms. Includes insight extraction and error analysis by sales segments

# Retail Sales Prediction – Machine Learning Project

This project develops a predictive analytics pipeline to understand and forecast unit sales of retail stores based on pricing, demographic, and merchandising factors. The goal is to identify key drivers of sales performance and compare machine learning models in terms of accuracy and interpretability.

## Objectives
- Perform exploratory data analysis to understand feature distributions and relationships.
- Preprocess data, including handling categorical variables and train/validation/test splitting.
- Build and evaluate two predictive models:
  - **Random Forest Regressor**
  - **Gradient Boosting Regressor**
- Compare model performance using MAE and RMSE metrics.
- Conduct error analysis to understand model behavior across different sales levels.

## Data & Features
The dataset contains store-level characteristics, including:

| Var. | Variable name | Description | Variable type | Code description |
|---|----------------|--------------|----------------|------------------|
| 1 | **Sales** | Unit sales (in thousands) at each location | Numerical | — |
| 2 | **CompPrice** | Price charged by competitor at each location | Numerical | — |
| 3 | **Income** | Community income level (in thousands of dollars) | Numerical | — |
| 4 | **Advertising** | Local advertising budget for company at each location (in thousands of dollars) | Numerical | — |
| 5 | **Population** | Population size in region (in thousands) | Numerical | — |
| 6 | **Price** | Price company charges for car seats at each site | Numerical | — |
| 7 | **ShelveLoc** | Quality of the shelving location for car seats (“Bad”, “Medium”, “Good”) | Categorical | “Bad”, “Medium”, “Good” |
| 8 | **Age** | Average age of the local population | Numerical | — |
| 9 | **Education** | Education level at each location | Numerical | — |
| 10 | **Urban** | Indicates whether the store is in an urban or rural location | Binary | 1: Yes, 0: No |
| 11 | **US** | Indicates whether the store is in the US or not | Binary | 1: Yes, 0: No |

Categorical variables are encoded using one-hot encoding.

## Methodology
1. **Exploratory Data Analysis (EDA)**
   - Histograms, boxplots, scatterplots, and correlation analysis.
2. **Preprocessing**
   - Dummy variable encoding for categoricals
   - Train/validation/test split (60/20/20)
3. **Modeling**
   - Hyperparameter tuning via cross-validation
   - Performance comparison on validation and test sets
4. **Feature Importance Analysis**
   - Identify key drivers influencing sales predictions
5. **Error Analysis**
   - Examine model performance across quartiles of predicted sales
  
