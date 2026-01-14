# Predicting Used Car Prices in the UK

## Project Overview
This project demonstrates a complete end-to-end data science pipeline, combining Exploratory Data Analysis (EDA) with Advanced Machine Learning to predict the selling price of used cars in the UK. By analysing features such as mileage, age, and engine size, the model helps uncover the key drivers of market value.

**Final Model Performance:**
*   **R² Score:** 0.92
*   **Mean Absolute Error (MAE):** £739 (42% improvement over baseline)

## Tools Used
*   **Python** (Pandas, NumPy)
*   **Visualisation** (Seaborn, Matplotlib)
*   **Machine Learning** (Scikit-Learn: Linear Regression, Ridge Regression, Random Forest, Gradient Boosting)

### Key Insights & Analysis

#### 1. Exploratory Data Analysis
Initial analysis revealed important patterns in the UK used car market:
* **Vehicle Age:** The #1 predictor of price, far outweighing mileage.
* **Regulatory Factors:** Euro 6 Compliance significantly impacts resale value due to ULEZ zones.
* **Non-Linearity:** The relationship between mileage and price is not linear; prices drop sharply initially and then plateau.

#### 2. Machine Learning Model
Built and compared multiple regression models to predict used car prices:
* **Linear Regression:** Baseline model for comparison.
* * **Ridge Regression (Log Transformed):** Handled skewed price distribution and regularisation to reduce overfitting.
* **Random Forest:** Captured non-linear relationships in the data.
* **Gradient Boosting:** Best performing model with R² of 0.92.

*View the full analysis here: [Used_Car_Prices.ipynb](Used_Car_Prices.ipynb)*

### Data Source

Dataset: [Used Cars Prices in UK](https://www.kaggle.com/datasets/muhammadawaistayyab/used-cars-prices-in-uk) from Kaggle

- **Author:** Muhammad Awais Tayyab
- **Description:** Vehicle listings scraped from AutoTrader.co.uk
- **Records:** 3,685 vehicles
- **Features:** 13 attributes including Price, Transmission, Mileage, Fuel Type, and Registration Year
- **Date Uploaded:** October 2023 (used as reference point for vehicle age calculations)

*See [used_cars_UK.csv](used_cars_UK.csv) for the full dataset.*
