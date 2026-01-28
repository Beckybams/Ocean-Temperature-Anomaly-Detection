📌 Project Overview

Ocean temperature anomalies, such as sudden warming or cooling events, can indicate climate change impacts, marine heatwaves, or abnormal oceanic conditions. This project demonstrates how synthetic ocean temperature data can be generated and analyzed to detect anomalies using both statistical and machine learning approaches.

🎯 Objectives

Simulate realistic daily ocean temperature data

Introduce artificial temperature anomalies

Detect anomalies using:

Z-Score (statistical method)

Isolation Forest (machine learning method)

Visualize detected anomalies

Export results for further analysis

🧪 Dataset Description

The dataset is synthetically generated to represent daily ocean surface temperatures.

Features:

Date – Daily timestamp

Temperature_C – Ocean temperature in Celsius

Z_Score – Standardized temperature score

Z_Anomaly – Z-score based anomaly flag (True/False)

IF_Anomaly – Isolation Forest anomaly flag (True/False)

🛠️ Methods Used
1️⃣ Z-Score Analysis

Identifies anomalies based on how far a temperature value deviates from the mean.

2️⃣ Isolation Forest

An unsupervised machine learning algorithm effective for detecting rare and abnormal patterns in data.

📊 Output

Time-series visualization of ocean temperatures

Highlighted anomaly points

Excel file containing full anomaly detection results

📁 Project Structure
Ocean-Temperature-Anomaly-Detection/
│
├── ocean_temperature_anomaly_detection.py
├── Ocean_Temperature_Anomaly_Detection.xlsx
├── README.md
🚀 How to Run

Install dependencies:

pip install numpy pandas matplotlib scikit-learn scipy openpyxl

Run the script:

python ocean_temperature_anomaly_detection.py
🌍 Applications

Marine heatwave monitoring

Climate change research

Oceanographic studies

Environmental early-warning systems

📝 Notes

This project uses synthetic data for demonstration and educational purposes. The same methodology can be applied to real-world satellite or buoy-based ocean temperature datasets.

📌 Future Improvements

LSTM-based time series anomaly detection

Real satellite or buoy data integration

Seasonal trend analysis

Dashboard visualization

🤝 Contributing

Contributions and improvements are welcome. Feel free to fork the project and submit a pull request.

📜 License
