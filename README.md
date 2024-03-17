# MPG Prediction Analysis

### Description:
This project uses regression models to predict automobile fuel efficiency (Miles Per Gallon). The [dataset](https://www.kaggle.com/datasets/uciml/autompg-dataset) used for analysis contains various attributes such as cylinders, displacement, horsepower, weight, acceleration, model year, and origin. The project involves data preprocessing, exploratory data analysis, model building, and evaluation.

### Steps Involved:
1. **Data Loading and Preprocessing:** The dataset is loaded into a Pandas DataFrame and preprocessed by removing unnecessary columns, handling missing values, and creating dummy variables for categorical features.
2. **Exploratory Data Analysis (EDA):** Correlation analysis and visualization are conducted to understand the relationship between different variables and the target variable (MPG). The analysis reveals significant correlations between MPG and various features.
3. **Model Building and Evaluation:**
  * **Ordinary Linear Regression:** The data is split into training and test sets, and a linear regression model is trained and evaluated using metrics like R-squared, RMSE, and MAE.
  * **Ridge Regression:** Another regression model, Ridge Regression, is implemented and evaluated using the same metrics to compare its performance with linear regression.

### Key Findings:
* Both linear regression and ridge regression models perform well in predicting MPG, with similar R-squared values on both training and test sets.
* The scatter plot of MPG versus weight exhibits a clear negative relationship, indicating that heavier vehicles have lower fuel efficiency.
* Ridge regression, despite its regularization, maintains parity with linear regression for MPG prediction, suggesting its effectiveness as an alternative when regularization is needed.

### Conclusion:
The analysis demonstrates that both linear regression and ridge regression are effective methods for predicting MPG. While linear regression provides a simple and interpretable model, ridge regression offers regularization to handle multicollinearity and improve generalization performance. The findings from this analysis can help understand and predict the fuel efficiency of automobiles, contributing to better decision-making in the automotive industry.

