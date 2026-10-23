# House Price Prediction

## Overview

This project uses Machine Learning to predict house sale prices based on various housing characteristics. It uses a **Random Forest Regressor** to learn patterns from historical housing data and generate price predictions for houses in the test dataset.

## Objectives

* Explore housing data using Python and Pandas.
* Train a Random Forest Regression model to predict house prices.
* Evaluate model performance using Mean Absolute Error (MAE).
* Generate predictions for unseen housing data.
* Export predictions to a CSV file for submission.

## Technologies Used

* **Python**
* **Pandas** for data loading and manipulation
* **Scikit-learn** for model training, validation, and evaluation
* **Random Forest Regressor** for house price prediction

## Dataset

This project uses the housing dataset from the Kaggle House Prices: Advanced Regression Techniques competition.

The dataset contains information about residential properties, including lot area, overall quality, year built, living area, number of bedrooms, bathrooms, and other features that may influence sale prices.

**Dataset source:** [Kaggle House Prices Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

The notebook expects the training and test datasets to be available as `train.csv` and `test.csv`.

*Note: The datasets are not included in this repository. Download them from the source above and configure the file paths before running the notebook outside Kaggle.*

## Methodology

1. **Data Loading:** Load the training dataset using Pandas.
2. **Feature Selection:** Select 25 housing-related features for model training.
3. **Data Splitting:** Divide the training data into training and validation sets.
4. **Model Training:** Train a Random Forest Regressor using the training data.
5. **Model Evaluation:** Calculate Mean Absolute Error (MAE) to assess prediction accuracy on the validation set.
6. **Final Training:** Train a new Random Forest Regressor using the complete training dataset.
7. **Price Prediction:** Predict sale prices for houses in the test dataset.
8. **Export Results:** Save the predictions in `submission.csv`.

## Evaluation Metric

The model uses **Mean Absolute Error (MAE)** to measure the average absolute difference between actual and predicted house prices on the validation set.

A lower MAE indicates that predictions are closer to the actual sale prices.

## How to Run

1. Clone or download this repository.

2. Download the training and test datasets from the Kaggle competition.

3. Install the required Python libraries:

   ```bash
   pip install pandas scikit-learn jupyter
   ```

4. Update the dataset paths in the notebook to match your local directory.

5. Open `House Price Prediction.ipynb` in Jupyter Notebook or Google Colab.

6. Run the notebook cells in order.

7. Find the generated predictions in `submission.csv`.

## Learning Outcomes

* Understanding supervised machine learning and regression.
* Working with structured datasets using Pandas.
* Selecting features for a predictive model.
* Training and evaluating a Random Forest Regressor.
* Generating predictions and exporting results to CSV.

## Author

**Seru Devaki Sananda**

This project was developed as part of my learning journey in Python and Machine Learning.

