Overview
This project creates synthetic data for CPU metrics like temperature, usage, and memory usage over a period of time. Anomalies are detected using statistical methods and visualized for better understanding.

Data Generation
Synthetic time-series data is generated for the following:

CPU Temperature: Random values between 30°C and 90°C.
CPU Usage: Random values between 0% and 100%.
Memory Usage: Random values between 20% and 80%.
The data is sampled at 20 Hz over 5 hours and stored in a CSV file named synthetic_time_series_data.csv.

Anomaly Detection
Anomalies are detected using Z-Scores:

Z-Score Calculation: Measures how far a value is from the mean in terms of standard deviation.
Threshold: Values with a Z-Score greater than ±3 are considered anomalies.
Visualization
CPU temperature data is plotted over time, with anomalies highlighted in red for easy identification.

How to Run
Clone the repository or download the script.
Install the necessary Python libraries listed in the requirements section.
Run the script to:
Generate data.
Save it to a CSV file.
Detect anomalies.
Visualize the results.
Requirements
Install the following Python libraries using pip:

pandas
matplotlib
numpy
Files
synthetic_time_series_data.csv: The generated dataset.
script.py: The Python script to generate, analyze, and visualize data.
