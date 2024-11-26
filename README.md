# ParticleCoordinateML

**Overview**
This repository implements a data-driven approach to predict particle positions in high-energy physics using data from a Resistive Silicon Detector (RSD). The goal is to accurately predict 2D spatial coordinates (X, Y) of particles based on signal features extracted from detector pads. The project applies advanced regression models and preprocessing techniques to ensure high predictive accuracy.

**Key Features**
Dataset: Includes 514,000 events with 12 signal features from detector pads (e.g., magnitude, delay, and area).
Regression Models: Implements multiple machine learning models (KNN, Random Forest, and MLP) for predicting spatial coordinates.
Preprocessing Pipeline:
Noise reduction and noisy pad elimination.
Outlier detection using Isolation Forest.
Feature selection through Random Forest importance analysis.
Evaluation Metric: Uses average Euclidean distance between predicted and actual coordinates.

**Results(Based on Euclidean Distance)**
KNN Regressor: 7.79
Random Forest Regressor: 4.98
Multi Layers Preceptrons: 4.32
