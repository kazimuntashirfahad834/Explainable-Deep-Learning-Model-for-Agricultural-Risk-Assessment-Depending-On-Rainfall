# Explainable-Deep-Learning-Model-for-Agricultural-Risk-Assessment-Depending-On-Rainfall
Explainable deep learning (CNN + BiLSTM + Attention) for monthly rainfall prediction in Bangladesh, with SHAP interpretability, extreme rainfall classification, and crop-level agricultural risk assessment.


AgriBD: Explainable Extreme Rainfall Prediction & Agricultural Risk Assessment

A time-series deep learning pipeline that forecasts monthly rainfall in Bangladesh and translates the predictions into actionable agricultural risk categories.

What it does

Trains a hybrid CNN + Bidirectional LSTM + Attention model on the Bangladesh Weather Dataset (Kaggle), using a 6-month sliding window of temperature and rainfall
Evaluates with RMSE, MAE, and R², plus a Low / Medium / Extreme rainfall classification (confusion matrix and classification report)
Explains predictions with SHAP (KernelExplainer) to show which lagged temperature and rainfall inputs drive the model
Analyzes actual vs. predicted rainfall across Bangladesh's seasons (Winter, Pre-Monsoon, Monsoon, Post-Monsoon)
Maps predictions to agricultural risk (drought, normal, flood, extreme flood) with affected crops and recommended actions
Generates a 12-month forward forecast with its associated risk levels
