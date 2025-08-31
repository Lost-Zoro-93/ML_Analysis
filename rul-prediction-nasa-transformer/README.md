# RUL Prediction with Transformers and LSTM Attention

This project predicts the Remaining Useful Life (RUL) of jet engines using the NASA C-MAPSS FD001 dataset. It implements and compares multiple models:

- **Bidirectional LSTM + Self-Attention**
- **Transformer Encoder**
- **Hybrid Ensemble Model**

The notebook includes robust data preprocessing, rolling window sequence modeling, and interpretable results using SHAP values and attention heatmaps. 
Evaluation is performed using RMSE and NASA’s asymmetric penalty score.

> 📊 Reproducible, interpretable, and aligned with real-world predictive maintenance use cases.
