# Sberbankhouse-price-prediction
# House Price Prediction

This project involves Basic Time Series Analysis & Feature Selection for predicting house prices.

## Introduction
🏆 Excited to Share Our Work on Predicting House Prices Using Time Series Analysis and Feature Selection!

Over the past few weeks, my partner and I worked on a project as part of our Machine Learning course to predict house prices based on a dataset spanning several years. The goal was to understand price behavior over time and select the most impactful features for accurate predictions.

**Our Approach:**

🛠️ **Building Baseline Models**: We started with regression models such as Random Forest and XGBoost to set a performance baseline. These models helped us establish a benchmark for future improvements.

🧹 **Data Cleaning**: Ensured data integrity by removing features with more than 20% missing values only if they had low correlation with the target variable. We also handled outliers manually to maintain the quality of the data. Additionally, we checked for high correlations between features and removed features that had a correlation close to 1 with each other and low correlation with the target variable.

💡 **Feature Engineering**: Created new features, including time-based variables and ratios, and leveraged insights from other Kaggle participants to generate meaningful variables. This step was crucial in enhancing the model's predictive power.

📊 **Exploratory Data Analysis**: Conducted thorough analysis to understand price distribution over different property types and demographic factors. We visualized the most correlated features and explored the impact of outliers to gain deeper insights into the data.

📈 **Time Feature Analysis**: Analyzed price changes over time using various time features (monthly averages, daily trends) to detect any significant trends. This analysis helped us understand the temporal dynamics of the housing market.

🔢 **Encoding Strategies**: Used target encoding for the sub_area feature because we recognized its importance and wanted to ensure it was accurately represented without introducing bias. We also converted other categorical variables to binary format to prevent overfitting and improve model performance.

🎯 **Model Training & Tuning**: Built separate models for different product types (Owner Occupier and Investment) and used Bayesian optimization for hyperparameter tuning. This approach allowed us to fine-tune the models for better accuracy and robustness.

🚀 **Model Enhancement**: Combined models and employed ensembling techniques to improve overall performance. By integrating multiple models, we were able to capture a wider range of patterns and enhance prediction accuracy.

**Result**: We successfully identified key trends and achieved accurate predictions with our enhanced models, achieving a public score of 0.31700. Proud to say we ranked in the top 25% out of over 3,450 participants!

I hope you find our work fascinating!

## How to Run
1. Clone the repository.
2. Install necessary dependencies.
3. Run the Jupyter notebook.

## Dependencies
- List of libraries and tools required to run the project:
  - numpy
  - pandas
  - scikit-learn
  - xgboost
  - etc.

## Conclusion
Insights and conclusions drawn from the project.
