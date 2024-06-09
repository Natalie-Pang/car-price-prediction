# Car Price Prediction

This repository contains a Jupyter notebook that demonstrates the use of a RandomForestRegressor to predict car prices. The notebook includes data preprocessing, model training, evaluation, and feature importance analysis.

## Project Overview

The goal of this project is to build a predictive model for car prices using the `RandomForestRegressor` from the `scikit-learn` library. The dataset used in this project is `car_price_prediction.csv`.

## Files in the Repository

- **Car_Price_Prediction.ipynb**: The main Jupyter notebook containing the code and analysis.
- **car_price_prediction.csv**: The dataset used for training and evaluating the model.

## Dataset

The dataset used in this project is downloaded from Kaggle: [Car Price Prediction Dataset](https://www.kaggle.com/datasets/sukhmandeepsinghbrar/car-price-prediction-dataset).


## Key Sections in the Notebook

1. **Data Loading and Preprocessing**:
    - Loading the dataset.
    - Handling missing values.
    - Encoding categorical variables.
    - Feature scaling.

2. **Model Training**:
    - Splitting the data into training and testing sets.
    - Initializing and training the `RandomForestRegressor`.

3. **Model Evaluation**:
    - Evaluating the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
    - Visualizing the model's predictions versus actual values.

4. **Feature Importance**:
    - Extracting feature importances from the trained model.
    - Sorting and visualizing the feature importances to understand which features contribute most to the model's predictions.

## Instructions to Run the Notebook

1. Clone this repository to your local machine:
    ```sh
    git clone https://github.com/Natalie-Pang/car-price-prediction.git
    ```
2. Navigate to the project directory:
    ```sh
    cd car-price-prediction
    ```
3. Open the Jupyter notebook:
    ```sh
    jupyter notebook Car_Price_Prediction.ipynb
    ```
4. Run all cells to execute the analysis.

## Results

The notebook concludes with an analysis of the feature importances, showing which features have the most significant impact on predicting car prices. The results are visualized in a sorted order, helping to highlight the most influential features.

## Conclusion

This project demonstrates how to use a Random Forest Regressor to predict car prices and analyze feature importances. The notebook provides a step-by-step guide, from data preprocessing to model evaluation and interpretation.

## Author

[Natalie Pang](https://github.com/Natalie-Pang)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
