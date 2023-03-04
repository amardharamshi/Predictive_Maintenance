# Predictive_Maintenance


# Challenge description

Assume you have a machine that produces a certain output. You have updated the machine with
the latest IoT device available on the market. The IoT device comes with 3 different sensors to
track machine health: temperature sensor, pressure sensor, and water level sensor. Machine
status is tracked automatically by the machine considering 4 modes: Running / Idle / Off / Failure.
Data transmission is at a frequency of 1 minute.

# Task-1: Generate random data with Python that supports the following assumptions:
A. Tags:
• Timestamp
• Temperature measurements
• Pressure measurements
• Water level measurements
• Machine status: Running / Idle / Off / Failure
B. Time period for data: 1 week
C. Data transmission issues:

a. Missing sensor measurements at random times and random periods due to
connectivity issues with the IoT device: e.g., sensor measurements are not being
transmitted, while machine status measurements are being transmitted correctly.
b. Faulty measurements: at random times and random periods one of the sensors
transmits static (constant) values.
c. Add random noise to your data.

# Task-2: What did you observe about the machine status based on the generated data?
# Task-3: Please build a model to predict machine status “Failure”.
# Task-4: How would you evaluate the performance of your model?
# Task-5: Based on the observations, how would you optimize your machine efficiency?
