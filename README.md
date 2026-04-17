# Telemetry Anomaly Detection

This project focuses on detecting anomalies in spacecraft telemetry data using machine learning techniques. The dataset is sourced from NASA's SMAP and MSL missions.

---

## Project Structure

telemetry-anomaly-detection/
├── anomaly_detection.ipynb
├── output.csv
├── README.md
├── requirements.txt

---

## Dataset

* Source: NASA Telemetry Dataset (SMAP & MSL) (https://www.kaggle.com/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl/data)
* Contains time-series sensor data from spacecraft
* Includes labeled anomaly intervals

---

## Features

* Data preprocessing and feature extraction
* Statistical feature engineering (mean, std, skewness, kurtosis)
* Multiple ML models:

  * Logistic Regression
  * Random Forest
  * SVM
  * XGBoost
* Model evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1-score
* Best model selection
* Output generation (`output.csv`)

---

## Approach

1. Load telemetry data
2. Extract statistical features
3. Train multiple models
4. Evaluate performance
5. Select best model
6. Generate predictions

---

## How to Run

Install dependencies:
pip install -r requirements.txt

Run the notebook:
jupyter notebook anomaly_detection.ipynb

---

## Output

* `output.csv` contains:

  * actual labels
  * predicted labels

---

## Tech Stack

* Python
* NumPy, Pandas
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn

---

## Future Improvements

* Use LSTM / Autoencoder for time-series anomaly detection
* Improve labeling strategy
* Hyperparameter tuning

---
