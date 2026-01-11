# Predicting Used Car Prices in the UK

## Project Overview
This project builds a machine learning pipeline to predict the selling price of used cars in the UK. By analysing features such as mileage, age, and engine size, the model helps uncover the key drivers of market value.

**Final Model Performance:**
*   **R² Score:** 0.92
*   **Mean Absolute Error (MAE):** £739 (42% improvement over baseline)

## Project Structure
*   `Used_Car_Prices.ipynb`: The main Jupyter Notebook containing the full analysis and code.
*   `used_cars_UK.csv`: The dataset used for training and testing.
*   `requirements.txt`: List of Python libraries required to run the project.

## Tech Stack
*   **Python** (Pandas, NumPy)
*   **Visualisation** (Seaborn, Matplotlib)
*   **Machine Learning** (Scikit-Learn: Linear Regression, Random Forest, Gradient Boosting)

## Key Insights
1.  **Vehicle Age** is the #1 predictor of price, far outweighing mileage.
2.  **Regulatory Factors** (Euro 6 Compliance) significantly impact resale value due to ULEZ zones.
3.  **Non-Linearity:** The relationship between mileage and price is not linear; prices drop sharply initially and then plateau.

## How to Run
1.  Clone the repository.
2.  Install dependencies: `pip install -r requirements.txt`
3.  Open `Used_Car_Prices.ipynb` in Jupyter Notebook.
