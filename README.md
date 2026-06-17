# Traffic-Volume-Prediction-Regression
Regression-based traffic volume forecasting system developed with Python, Pandas, Scikit-learn, and Google Colab.
# 🚦 Traffic Volume Prediction Using Regression

## Overview

This project predicts traffic volume using machine learning regression techniques based on weather conditions and time-related factors. The goal is to analyze historical traffic data and build a model capable of estimating the number of vehicles on a roadway at a given time.

## Dataset Features

The dataset contains the following attributes:

* `traffic_volume` – Number of vehicles (Target Variable)
* `holiday` – Holiday information
* `temp` – Temperature
* `rain_1h` – Rainfall in the last hour
* `snow_1h` – Snowfall in the last hour
* `clouds_all` – Cloud coverage percentage
* `weather_main` – Main weather condition
* `weather_description` – Detailed weather condition
* `date_time` – Date and time of observation

## Project Workflow

1. Data Collection and Loading
2. Data Cleaning and Preprocessing
3. Missing Value Handling
4. Date-Time Feature Extraction
5. Categorical Feature Encoding
6. Feature Scaling
7. Train-Test Split
8. Linear Regression Model Training
9. Traffic Volume Prediction
10. Model Evaluation

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

## Machine Learning Model

The project uses **Linear Regression** to predict traffic volume based on weather and temporal features.

### Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Project Structure

```text
TRAFFIC_VOLUME_PREDICTION/
│
├── TRAFFIC_VOLUME_PREDICTION.ipynb
├── dataset.csv
├── README.md
└── requirements.txt
```

## Results

The model learns patterns between weather conditions, time factors, and traffic volume to generate predictions. The performance is evaluated using standard regression metrics to measure prediction accuracy.

## Future Improvements

* Random Forest Regression
* Gradient Boosting Regression
* XGBoost Regressor
* Hyperparameter Tuning
* Traffic Volume Forecasting Dashboard
* Real-Time Traffic Prediction

## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/TRAFFIC_VOLUME_PREDICTION.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook TRAFFIC_VOLUME_PREDICTION.ipynb
```

4. Run all cells to train the model and generate predictions.

## Author

Developed as a Machine Learning Regression Project for Traffic Volume Prediction using weather and time-based features.
