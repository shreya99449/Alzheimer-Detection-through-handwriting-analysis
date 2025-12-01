Handwriting-Based Early Alzheimer’s Detection (DARWIN Dataset)

A production-grade pipeline for classifying early-stage Alzheimer’s disease using handwriting dynamics. The stack benchmarks CatBoost, Random Forest, LSTM, BiLSTM-Attention, and Transformer Encoder models on the DARWIN dataset, delivering a full workflow from preprocessing → model training → evaluation → explainability.

Key Features

End-to-end pipeline: cleaning, normalization, feature engineering, temporal sequence prep.

ML & DL benchmarks with metrics: Accuracy, AUC, F1-macro, Sensitivity, Specificity.

SHAP-based interpretability to identify critical biomarkers (in-air time, pressure variability, shakiness, speed).

Modular codebase ready for rapid experimentation and downstream deployment.

Tech Stack

Python, NumPy, Pandas, Scikit-Learn

TensorFlow / PyTorch (depending on your LSTM/Transformer build)

SHAP, Matplotlib, Seaborn

Dataset

This project uses the DARWIN Handwriting Dataset, containing digitized handwriting signals (position, pressure, tilt, timestamps) from Alzheimer’s vs healthy controls performing structured tasks.

(Dataset not redistributed. Obtain from the official source.)

Model Suite

CatBoost — top ML performer (AUC ≈ 0.93)

LSTM — best DL temporal model (AUC ≈ 0.88)

BiLSTM + Attention

Transformer Encoder

Random Forest / XGBoost baselines
