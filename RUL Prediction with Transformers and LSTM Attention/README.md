# 🔧 Remaining Useful Life (RUL) Prediction using LSTM, Transformer, and Ensembles

This project implements advanced machine learning and deep learning models to predict the **Remaining Useful Life (RUL)** of jet engines using the **NASA C-MAPSS FD001** dataset.

We apply:
- **LSTM + Self-Attention**
- **Transformer Encoder**
- **Ensemble Learning**  
With full interpretability using **SHAP** and **attention heatmaps**.

> ⚠️ Predictive maintenance is critical in aerospace and manufacturing industries. This project demonstrates a reproducible, interpretable approach to high-stakes time-series modeling.

---

## 📊 Problem Statement

Given multivariate time-series sensor data from multiple engines running until failure, predict the Remaining Useful Life (RUL) at each timestep.

---

## 🧠 Models Used

| Model             | Description                                          |
|------------------|------------------------------------------------------|
| **LSTM + Attention** | Sequence model with BiLSTM and multi-head attention |
| **Transformer**       | Lightweight Transformer Encoder (learnable position embeddings) |
| **Ensemble**          | Averaging predictions from LSTM and Transformer     |

---

## 📈 Evaluation Metrics

- **RMSE** (Root Mean Squared Error)
- **NASA Score**: Asymmetric penalty that heavily penalizes late predictions

| Model        | RMSE   | NASA Score |
|--------------|--------|------------|
| LSTM-Attn    | 13.88  | 34,356     |
| Transformer  | 19.54  | 121,291    |
| **Ensemble** | 14.93  | 39,401     |

---

## 🧪 Dataset

- 📦 NASA C-MAPSS FD001
- Multivariate time-series data from turbofan engines
- 21 sensor readings + 3 operating settings per engine cycle

> Data not included in repo. Download from:  
> https://www.kaggle.com/datasets/behrad3d/nasa-cmaps
