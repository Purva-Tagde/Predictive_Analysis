# Air Quality Index (AQI) Prediction Using Machine Learning

## Project Overview

This project develops a machine learning model to estimate the Air Quality Index (AQI) using environmental pollutant concentrations and meteorological factors. A Random Forest Regression model is trained and evaluated, and an interactive dashboard allows users to enter environmental values and view the predicted AQI.

## Problem Statement

Air quality is affected by pollutants and weather conditions. This project aims to estimate AQI from these environmental variables and identify the factors associated with changes in air quality.

## Dataset

The project uses a Delhi air quality and weather dataset containing pollutant measurements and meteorological variables.

**Dataset source:** https://huggingface.co/datasets/abhinavsarkar/delhi_air_quality_feature_store_processed.csv

The original dataset contains approximately 2.9 million records. A sample of 100,000 records was used for the current notebook.

## Input Features

* PM2.5 and PM10
* Nitrogen dioxide (NO₂)
* Sulphur dioxide (SO₂)
* Ozone (O₃)
* Carbon monoxide (CO)
* Temperature
* Humidity
* Atmospheric pressure
* Wind speed

## Methodology

1. Problem identification
2. Dataset loading and understanding
3. Data cleaning and preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature and target selection
6. Training and testing split
7. Random Forest Regression model training
8. Model evaluation using MAE, MSE, RMSE and R²
9. Feature relationship and importance analysis
10. AQI prediction for new input values

## Technologies Used

* Python
* Pandas and NumPy
* Matplotlib
* Scikit-learn
* Google Colab
* Gradio (if used in the dashboard)

## Repository Contents

* `AQI_Prediction_Predictive_Analytics.ipynb` — complete notebook
* `KNN.ipynb` — additional coursework notebook
* `Regression_Tree.ipynb` — additional coursework notebook
* `README.md` — project documentation

## Limitations

The current model estimates AQI using pollutant and weather readings supplied at the same time. It should not be described as a future AQI forecasting system. The reported performance should be interpreted carefully because AQI may be closely related to the pollutant measurements used as input.

## Disclaimer

This is an academic predictive analytics project. Its output is an estimate and should not replace official air-quality measurements or public-health guidance.
