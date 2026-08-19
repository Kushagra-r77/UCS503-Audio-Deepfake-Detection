# UCS503-Audio-Deepfake-Detection
This project proposes a full-stack Audio Deepfake Spoofing Detection System that combines audio signal 
processing, machine learning, explainable AI, and relational data management. 
The central engineering pipeline transforms raw audio into Mel-spectrograms and uses a custom-trained 
CNN to distinguish between genuine and synthetic speech. The system extends beyond basic classification 
by investigating performance under audio degradation and different recording durations, while Grad-CAM 
provides a visual interpretation of the model's predictions. 
An SQL database will maintain prediction and experiment telemetry, enabling historical analysis of model 
behavior across different conditions and model versions. 
The project therefore emphasizes not only the development of a working AI classifier, but also data 
transformation, measurable evaluation, robustness testing, explainability, and deployable software 
architecture. 

The final prototype will demonstrate the complete workflow: 

Audio Upload → Preprocessing → Mel-Spectrogram → Custom CNN → Real/Fake Prediction →  
Confidence + Grad-CAM Explanation → SQL Logging 

This makes the project a practical engineering system for investigating the detection of synthetic speech 
while providing clear opportunities for experimentation, evaluation, and future expansion.
