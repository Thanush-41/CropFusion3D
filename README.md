# CropFusion3D: Deep Learning Model for Crop Yield Forecasting in Andhra Pradesh

##  Overview

**CropFusion3D** is a deep learning model that combines **3D Convolutional Neural Networks (3D-CNN)**, **Gated Recurrent Units (GRU)**, and an **attention mechanism** to deliver accurate crop yield forecasting. The project focuses on the agricultural region of **Andhra Pradesh, India**, utilizing diverse agricultural datasets to predict crop yields across seasons and conditions.

---

##  Key Features

- Integration of **spatiotemporal data** (climate, soil, irrigation, and crop features)
- Advanced **hybrid model architecture**: 3D-CNN + GRU + Attention
- Achieved **91% accuracy** and **0.65 MSE**
- Offers **interpretable predictions** with attention-based weighting
- Supports **data-driven agriculture** and policymaking

---

##  Methodology: CropFusion3D Architecture

### 🔧 Components:
- **3D-CNN**: Extracts spatial-temporal features from multi-dimensional data (e.g. satellite images, rainfall).
- **GRU**: Models temporal dependencies in weather and crop patterns.
- **Attention Mechanism**: Highlights most important time steps and features.

###  Dataset:
- 20,000+ samples across districts in Andhra Pradesh
- Features: land area, rainfall, temperature, humidity, irrigation, fertilizer usage, crop yield
- Sourced from government portals and preprocessed with data augmentation

### 📊 Performance:
| Model              | Accuracy (%) | MSE   | Precision | Recall |
|-------------------|--------------|-------|-----------|--------|
| Linear Regression | 75.2         | 1.32  | 0.78      | 0.65   |
| Random Forest     | 85.5         | 0.89  | 0.84      | 0.78   |
| LSTM              | 88.7         | 0.74  | 0.87      | 0.81   |
| **CropFusion3D**  | **91.0**     | **0.65** | **0.89**  | **0.85** |

---



##  Evaluation Metrics

- **Accuracy**: 91%
- **MSE**: 0.65
- **Precision & Recall**: 0.89 & 0.85 respectively
- **F1-Score**: Macro avg 0.73, Weighted avg 0.89
- **AUC Score**: 0.93
- **Classification Report**: High performance on majority class

---



##  Future Work

- Expand model generalization to multiple crop types
- Integrate real-time satellite and IoT sensor data
- Add explainability with XAI tools
- Explore deployment for real-time farming assistance

---

##  Authors

- Karthika Natarajan
- Thanush Chowdary Garimella
- Lohitha Koneru
- Likith Kalavandala

---

## 📄 License

This project is licensed under the MIT License.
