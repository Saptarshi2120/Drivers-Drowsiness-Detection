# Drivers Drowsiness Detection using neural networks

*Overview*

This project implements a driver drowsiness detection system using transfer learning with the Inception V3 neural network architecture. The system is designed to analyze facial features from real-time camera data to identify signs of driver fatigue or drowsiness. The model has been trained on a specific dataset to recognize patterns associated with drowsiness, enabling it to provide timely alerts to the driver.

Features
Transfer Learning: The Inception V3 model, pre-trained on a large dataset, is fine-tuned using a specialized dataset for driver drowsiness detection. Transfer learning helps leverage the knowledge gained from the broader dataset for improved performance on the specific task.

Real-time Facial Analysis: The system captures facial images from a live camera feed, preprocesses them, and feeds them into the Inception V3 model for analysis. The model extracts relevant features and makes predictions on the driver's alertness.

Alert Mechanism: When signs of drowsiness are detected, the system triggers alerts to notify the driver. This may include visual warnings or auditory alarms to prompt the driver to take corrective action.

Dataset
The project utilizes a custom dataset specifically curated for driver drowsiness detection. The dataset includes a diverse range of facial images captured under different lighting conditions and driver states.
