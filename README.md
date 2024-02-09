# Anomaly-Detection-for-Industrial-Sensors

Anomaly Detection in Sensor Data using Isolation Forest

This notebook demonstrates how to perform anomaly detection on sensor data using the Isolation Forest algorithm. Anomaly detection is a critical task in various domains such as industrial monitoring, cybersecurity, and fraud detection. In this example, we focus on detecting anomalies in sensor data collected from a system using Isolation Forest, a popular algorithm for outlier detection.

Key Steps:

Data Loading and Preprocessing:

The sensor data is loaded from a CSV file and preprocessed to handle missing values. In this example, missing values are filled with the median of each column.
Model Training:

An Isolation Forest model is initialized and trained using the preprocessed sensor data. Isolation Forest is an effective algorithm for anomaly detection, especially in high-dimensional datasets like sensor data.
Anomaly Detection:

The trained model is used to predict anomalies in the sensor data. Anomalies are identified based on anomaly scores computed by the Isolation Forest model.
Visualization:

The detected anomalies are visualized alongside the sensor data and anomaly scores. This visualization provides insights into the anomalies detected by the Isolation Forest algorithm.
Results and Insights:

The visualization shows anomalies highlighted in red, allowing for easy identification of abnormal patterns in the sensor data.
Anomaly detection using Isolation Forest can be valuable for proactive maintenance, early fault detection, and ensuring the reliability of systems in various applications.
