# Tire Cost Analysis and Prediction

This project analyzes tire cost data from 2023 and 2024 to understand cost trends and build a predictive model for future tire costs.

**Data Processing:**

1. Imports tire cost data from Excel files using Pandas.
2. Cleans and preprocesses the data, including renaming columns, handling missing values, and merging datasets.
3. Extracts relevant features like tire dimensions (width, aspect ratio), seasonality, and previous year's cost.

**Data Analysis:**

1. Calculates and visualizes the average cost of tires for different seasons (summer, winter).
2. Identifies the most common tire figures and their associated costs.
3. Analyzes the cost increase rate from 2023 to 2024, overall and by season.
4. Explores the relationship between tire dimensions and cost.

**Predictive Modeling:**

1. Builds a Linear Regression model to predict 2024 tire costs based on features like dimensions, season, and 2023 cost.
2. Evaluates the model's performance using metrics like Mean Squared Error (MSE) and R-squared (R²).
3. Experiments with Polynomial Regression and Random Forest Regression models to improve prediction accuracy.
4. Visualizes the model's predictions against actual values.

**Key Findings:**

* **Cost Increase:** The average cost of tires increased significantly from 2023 to 2024.
* **Seasonal Variation:** Summer tires generally have a higher average cost compared to winter tires.
* **Predictive Accuracy:** The Random Forest model achieved the highest accuracy in predicting 2024 tire costs.

**Future Work:**

* Explore additional features for model improvement.
* Develop a web application for interactive cost prediction.
* Analyze the impact of external factors like currency exchange rates on tire costs.
