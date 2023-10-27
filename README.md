# retail_sales_prediction

📈 Workflow
Here's a brief overview of our workflow for this project:

Data Loading and Preprocessing: Load the data and preprocess it for analysis and modeling. This includes converting date columns to datetime format and extracting additional date-related features.

Exploratory Data Analysis (EDA): Perform exploratory data analysis to gain insights into the dataset, understand the distributions of features, and explore potential relationships between the features and sales.

Feature Engineering: Perform feature engineering to extract additional relevant features or transform existing features to improve the model's performance.

Model Training and Validation: Train the LightGBM model using a GroupKFold cross-validation strategy and make predictions on the test set.

Sales Disaggregation: Disaggregate the forecasted total sales into product-level sales using historical sales ratios.

Model Evaluation: Evaluate the performance of the trained model using appropriate evaluation metrics and assess the model's ability to generalize to unseen data using the test set.

Prediction and Deployment: Use the trained model to make predictions on new, unseen data. If applicable, deploy the model for practical use or further analysis.

