# Carbon Emission Prediction

## Project Overview
Carbon Emission Prediction is a machine learning project that estimates carbon emissions based on lifestyle habits, transportation choices, energy consumption, and other personal factors. The project applies regression techniques to identify patterns in the data and predict carbon emission values.

## Objectives
- Understand and preprocess the dataset.
- Perform exploratory data analysis and feature engineering.
- Build and evaluate regression models.
- Compare Linear Regression, Ridge, Lasso, Random Forest, and Gradient Boosting.
- Evaluate model performance using MAE, RMSE, and R².
- Identify important features influencing carbon emission predictions.

## Dataset
The project uses the **Carbon Emission - LMS** dataset.

- **Target variable:** `CarbonEmission`
- **Dataset size:** 10,000 rows and 20 original columns.
- **Features include:** Body Type, Sex, Diet, Transport, Vehicle Type, Monthly Grocery Bill, Frequency of Traveling by Air, Vehicle Monthly Distance, Energy efficiency, Recycling, and other lifestyle-related variables.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models
The following regression models were implemented and compared:

1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. Random Forest Regressor
5. Gradient Boosting Regressor

## Model Evaluation
The models were evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and the R² score.

### Best Model: Gradient Boosting Regressor

| Evaluation Metric | Test Result |
|---|---:|
| MAE | 151.28 |
| RMSE | 204.88 |
| R² Score | 0.9596 |

The Gradient Boosting model achieved the best performance among the models tested, explaining approximately 95.96% of the variation in the target values on the test set.

### Important Features
The feature importance analysis identified the following influential features:

- Vehicle Monthly Distance Km
- Frequency of Traveling by Air
- Vehicle Type (electric)

Feature importance indicates how much a feature contributes to the trained model's predictions. It does not necessarily establish a causal relationship with carbon emissions.

## Project Structure

```text
Carbon-Emission-Prediction/
├── README.md
├── Carbon Emission - LMS.csv
└── Carbon_Emission_Prediction.ipynb
```

*Note: Replace the filenames above with your actual uploaded filenames if they differ.*

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Ensure the dataset is available at the path specified in the notebook.
5. Run the notebook cells in order.

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Conclusion
This project developed and compared multiple regression models to predict carbon emissions using lifestyle and transportation data. Gradient Boosting achieved the best test performance, with an MAE of 151.28, an RMSE of 204.88, and an R² score of 0.9596. Feature importance analysis highlighted vehicle distance, air travel frequency, and electric vehicle type among the influential predictors. The results demonstrate the potential of machine learning for estimating carbon emissions from observed lifestyle patterns.

## Author
**Chandana Yemul**
