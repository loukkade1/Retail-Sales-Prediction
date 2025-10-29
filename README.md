# Retail-Sales-Prediction
Developed a predictive analytics pipeline to identify key drivers of product sales and evaluate model performance across Random Forest and Gradient Boosting algorithms. Includes insight extraction and error analysis by sales segments

# Retail Sales Prediction – Machine Learning Project

This project develops a predictive analytics pipeline to understand and forecast unit sales of retail stores based on pricing, demographic, and merchandising factors. The goal is to identify key drivers of sales performance and compare machine learning models in terms of accuracy and interpretability.

## 📊 Objectives
- Perform exploratory data analysis to understand feature distributions and relationships.
- Preprocess data, including handling categorical variables and train/validation/test splitting.
- Build and evaluate two predictive models:
  - **Random Forest Regressor**
  - **Gradient Boosting Regressor**
- Compare model performance using MAE and RMSE metrics.
- Conduct error analysis to understand model behavior across different sales levels.

## 🧠 Data & Features
The dataset contains store-level characteristics, including:

| Feature | Description | Type |
|--------|-------------|------|
| Sales | Unit sales (target variable) | Numerical |
| Price | Product price at store | Numerical |
| CompPrice | Competitor price | Numerical |
| Advertising | Local advertising budget | Numerical |
| Income | Community income level | Numerical |
| Population | Population in region | Numerical |
| ShelveLoc | Quality of product shelf placement | Categorical |
| Urban, US | Store location characteristics | Binary |

Categorical variables are encoded using one-hot encoding.

## 🔧 Methodology
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
  
