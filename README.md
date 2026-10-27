# NYC Airbnb Price Prediction

## Project Overview

This project uses Machine Learning to predict Airbnb listing prices in New York City using **Linear Regression**.

The goal is to explore how listing characteristics, such as location, room type, minimum nights, reviews, and availability, relate to Airbnb prices.

## Objectives

- Explore and understand the Airbnb listings dataset.
- Clean the data and handle missing values.
- Treat extreme values in price and minimum nights using the 95th percentile rule.
- Convert categorical features using One-Hot Encoding.
- Train and evaluate a Linear Regression model.
- Interpret the model's performance from a business perspective.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Data loading and initial exploration
2. Data cleaning and missing-value handling
3. Outlier treatment
4. Exploratory Data Analysis (EDA)
5. Categorical feature encoding
6. Train-test split (80:20)
7. Linear Regression model training
8. Model evaluation and interpretation

## Model Performance

The Linear Regression model achieved the following results on the test dataset:

| Metric | Result |
|---|---:|
| R² Score | 0.47 |
| Mean Absolute Error (MAE) | $38.54 |

### Interpretation

The R² score of 0.47 indicates that the model explains approximately 47% of the variation in Airbnb listing prices on the test dataset.

The MAE of $38.54 means that the average absolute difference between predicted and actual prices is approximately $38.54, assuming the target prices are measured in US dollars.

The model provides a baseline estimate of listing prices, but its predictions are not exact. Prediction errors were larger for higher-priced listings, suggesting that additional features or a more flexible model may improve performance.

## Key Takeaways

- Location and room type are useful characteristics to investigate when understanding Airbnb prices.
- Data cleaning and categorical encoding are important parts of the machine learning workflow.
- Linear Regression provides an interpretable baseline for a price prediction problem.
- More advanced models and additional listing features could be explored to improve prediction accuracy.

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook in VS Code or Jupyter Notebook.
4. Ensure the dataset is available at the file path expected by the notebook.
5. Run the notebook cells in order.

## Limitations and Future Improvements

- Explore additional features that may explain differences in listing prices.
- Compare Linear Regression with models such as Decision Tree and Random Forest.
- Evaluate residuals and investigate prediction errors for expensive listings.
- Use cross-validation to assess model stability.


## Disclaimer

This project is for educational and analytical purposes. Predictions should be treated as estimates, not guaranteed Airbnb listing prices.
