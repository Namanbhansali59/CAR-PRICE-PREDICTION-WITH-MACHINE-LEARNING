# Car Price Prediction with Machine Learning

This repository contains a machine learning project to predict car prices using a dataset with various car features. The project includes data exploration, preprocessing, model training, and evaluation.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Visualizations](#visualizations)
- [Skills Acquired](#skills-acquired)
- [License](#license)

## Overview
Car price prediction is a significant research area in machine learning. This project aims to build a predictive model to estimate car prices based on various features such as brand, year, fuel type, transmission, and more.

## Dataset
The dataset used in this project contains the following columns:
- `Car_Name`
- `Year`
- `Selling_Price`
- `Present_Price`
- `Driven_kms`
- `Fuel_Type`
- `Selling_type`
- `Transmission`
- `Owner`

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Namanbhansali59/car-price-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd car-price-prediction
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the Jupyter Notebook, use the following command:
```bash
jupyter notebook Car_Price_Prediction.ipynb
```
Follow the steps in the notebook to explore the data, preprocess it, train the model, and evaluate its performance.

## Results
The Random Forest Regressor model was trained to predict car prices with a Mean Absolute Error (MAE) of `X`. Feature importance analysis showed that `Present_Price` and `Year` were the most significant predictors.

## Visualizations
 Refer to linkedin post : https://www.linkedin.com/posts/naman-jain-3247831b7_oasisinfobyte-machinelearning-carpriceprediction-activity-7221717106554290177-xgbD?utm_source=share&utm_medium=member_desktop

## Skills Acquired
- Data Visualization
- Feature Importance Analysis
- Model Performance Evaluation

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
