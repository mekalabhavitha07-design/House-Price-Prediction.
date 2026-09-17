# House-Price-Prediction.
Developed a machine learning-based House Price Prediction model using Python and Scikit-learn to estimate property sale prices from housing features. The project involved loading and exploring the dataset using Pandas, identifying numerical and categorical variables, and analyzing relationships between numerical features using correlation heatmaps. Categorical feature distributions and unique values were also visualized using Matplotlib and Seaborn.

Data preprocessing included removing the unnecessary Id column, handling missing values in the SalePrice feature using mean imputation, and removing remaining incomplete records. Categorical variables such as MSZoning, LotConfig, BldgType, and Exterior1st were transformed into numerical representations using One-Hot Encoding with handling for previously unseen categories.

The processed dataset was divided into training and validation sets using an 80:20 split. Multiple machine learning regression approaches were implemented and evaluated, including Support Vector Regression (SVR), Random Forest Regression, and Linear Regression. Model performance was measured using Mean Absolute Percentage Error (MAPE) to compare prediction accuracy on validation data.

This project provided practical experience in data preprocessing, exploratory data analysis, feature encoding, train-validation splitting, regression modeling, and model evaluation using Python, Pandas, Matplotlib, Seaborn, and Scikit-learn.
