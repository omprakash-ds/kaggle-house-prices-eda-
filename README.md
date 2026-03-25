# House Prices - Advanced Regression Techniques

End-to-end EDA and modeling project from Kaggle competition.

## Overview
Built a house price prediction model using 79 features from the Ames, Iowa dataset. Focused on thorough EDA, feature engineering, and business insights.

## Key Findings
- OverallQual (0.79) is the strongest predictor of SalePrice
- TotalSF (engineered feature) outperforms individual floor areas
- Location (Neighborhood) creates 3x price variation
- Newer houses (post-2000) show significant premium

## Data Quality
- Handled 19 columns with missing values using context-aware strategies ("None" for absent features, median for LotFrontage, etc.)
- Removed 2 extreme outliers in GrLivArea
- Applied log transformation to SalePrice (skewness reduced from 1.88 to 0.12)

## Next Steps (Modeling Phase)
- Categorical encoding (OneHot + Target encoding)
- Baseline Linear Regression → Random Forest → XGBoost
- Evaluation using RMSLE
- Streamlit deployment for interactive price prediction

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn

Live demo coming soon (Streamlit).
