# osteoporosis_xai_thesis
Comparative Explainable AI framework for osteoporosis risk prediction using knee X-ray imaging and lifestyle data

This repository contains my undergraduate thesis work on building an explainable AI framework for osteoporosis risk prediction using two independent modalities: knee X-ray images and lifestyle risk factors.

## Overview
The goal of this project is to compare model performance and interpretability across imaging and tabular data.

##Methods
- CNN models: ResNet50, EfficientNetB2, Xception (transfer learning)
- Classical ML: LightGBM, XGBoost, Random Forest
- Ensemble learning for final predictions

## Explainability
- Grad-CAM for visual interpretation (image data)
- SHAP for feature importance (tabular data)

## Evaluation Metrics
- Accuracy
- F1-score
- ROC-AUC

## Tech Stack
- Python
- PyTorch / TensorFlow
- Scikit-learn
- LightGBM, XGBoost
- SHAP
