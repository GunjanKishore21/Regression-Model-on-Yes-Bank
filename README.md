# Regression-Model-on-Yes-Bank

The project focused on predicting stock prices using historical data. The dataset underwent thorough cleaning to handle missing values, correct data types, and manage outliers, ensuring data quality. Categorical variables were encoded, and numerical features were scaled for optimal modeling.

A Ridge regression model was selected for its ability to manage multicollinearity and prevent overfitting. Hyperparameter tuning using GridSearchCV identified the best model with an optimal alpha value of 0.1.

The model demonstrated strong performance during evaluation on both training and test datasets. It achieved a high R-squared score of 0.98 before and 0.97 after hyperparameter tuning.Mean squared error (MSE) metrics were also low, with values of 39.03 before and 55.98 after tuning, highlighting the model's predictive accuracy.

Exploratory Data Analysis (EDA) provided insights into stock price trends and relationships between variables. Visualizations such as line plots and scatter plots facilitated understanding of data patterns and influential factors affecting stock prices.

In summary, the project successfully applied machine learning techniques, specifically Ridge regression, to predict stock prices. Rigorous data preprocessing, effective model selection through hyperparameter tuning, and comprehensive evaluation metrics underscored the project's methodology and findings. Future work could explore additional models or advanced feature engineering techniques to further enhance predictive capabilities.
