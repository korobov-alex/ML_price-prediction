# ML_price-prediction

This repository contains code for a machine learning project aimed at predicting housing prices in Amsterdam. The project involves data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation. Below is an overview of the project structure and key components.

## Project Structure

- `README.md`: Overview of the project, instructions, and information for users.
- `housing_price_prediction.ipynb`: Jupyter Notebook containing the complete code for the project.
- `HousingPrices-Amsterdam-August-2021.csv`: Dataset used for analysis and modeling.
- `LICENSE`: License information for the project.
- `requirements.txt`: File containing the list of Python libraries required to run the code.

## Instructions

To run the code and reproduce the results:

1. Clone this repository to your local machine.
2. Ensure you have Python installed on your system.
3. Install the required Python libraries by running:
   ```
   pip install -r requirements.txt
   ```
4. Open and run the Jupyter Notebook `housing_price_prediction.ipynb` using Jupyter Notebook or JupyterLab.

## Dataset

The dataset used in this project (`HousingPrices-Amsterdam-August-2021.csv`) contains information about housing prices in Amsterdam. It includes various features such as address, location coordinates, zip code, price, etc.

## Code Overview

- **Data Preprocessing**: 
  - Handling missing values.
  - Removing outliers.
  - Encoding categorical variables.
  - Calculating distance to the city center.

- **Exploratory Data Analysis (EDA)**:
  - Visualizing relationships between variables.
  - Identifying correlations between features.
  - Understanding data distributions.

- **Feature Engineering**:
  - Calculating additional features such as distance to the city center.

- **Model Building**:
  - Implementing various regression algorithms including Linear Regression, Decision Tree, Random Forest, K-Nearest Neighbors, and XGBoost.
  - Constructing pipelines for each model including data preprocessing steps.

- **Model Evaluation**:
  - Cross-validation to assess model performance.
  - Evaluation metrics such as R-squared, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

## Results

The project evaluates multiple regression models and identifies Random Forest as the best-performing model based on R-squared and other evaluation metrics.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Author

- [Your Name](https://github.com/korobov-alex)

Feel free to reach out with any questions or feedback!
