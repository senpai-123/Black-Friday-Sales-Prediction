# Black-Friday-Sales-Prediction
This repository contains a Jupyter Notebook focused on predicting Black Friday sales using various machine learning models. The project utilizes popular Python libraries, including pandas, seaborn, matplotlib, numpy, and scikit-learn.

Linear Regression:
The project employs Linear Regression to predict Black Friday sales. Key evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) are utilized to assess the model's accuracy on the test data.

Decision Tree Regressor:
A Decision Tree Regressor is implemented for sales prediction. The model is evaluated using MAE, MSE, and R2, providing insights into its predictive performance.

Random Forest Regressor:
The Random Forest Regressor, known for its ensemble learning capabilities, is utilized for sales prediction. Evaluation metrics are computed to gauge the model's accuracy.

XGBoost Regressor:
XGBoost, a powerful boosting algorithm, is employed to enhance predictive capabilities. The model is evaluated using MAE, MSE, and R2 to assess its performance on the test data.

To optimize the dataset for model training, columns with non-significant impact are dropped. The resulting DataFrame is saved as a CSV file named "Result.csv" for further analysis.
