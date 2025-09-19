# 🌍 Air Quality Index (AQI) Anomaly Detection

This project implements an Anomaly Detection Model for Air Quality Index (AQI) values. It classifies normal vs anomalous AQI readings using the Isolation Forest algorithm.

# 📌 Project Overview

Input Data: Air Quality Index values from a CSV file.

Model: Isolation Forest (unsupervised anomaly detection).

Threshold: AQI values within the 22–274 range are considered normal. Values outside this range are flagged as anomalies.

Deployment Ready: The project includes data preprocessing, model training, and anomaly prediction on new CSV inputs.

# 🚀 Features

✅ Detects anomalous AQI readings.
✅ Flags AQI values above 300 as anomalies.
✅ Adjustable contamination rate (default: 5%).
✅ Deployment-ready with CSV support.
✅ Clean classification report for AQI categories.

# 🛠️ Tech Stack

Python 3.9+

Libraries:

pandas

numpy

scikit-learn

matplotlib (optional for visualization)
