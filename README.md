# QML Embeddings and Canonical ML Model Performance Comparison

## Overview
This project explores the impact of quantum machine learning (QML) embeddings on classical machine learning models. We implement two types of QML embeddings—angle embedding and amplitude embedding—before applying canonical machine learning models. The results are then compared with models trained without QML embeddings to analyze their effectiveness.

## Methodology
The following steps were followed in this project:

1. **Data Preprocessing**: Standard preprocessing techniques were applied to prepare the dataset for analysis.
2. **Datasets**:
   - The models were trained and evaluated on ISCX datasets provided by the University of New Brunswick (UNB).
3. **Quantum Embeddings**:
   - **Angle Embedding**: Encodes classical data as quantum states using angle-based parameterization.
   - **Amplitude Embedding**: Maps classical data to quantum states by normalizing feature vectors.
4. **Canonical ML Models**:
   - k-Nearest Neighbors (KNeighborsClassifier)
   - Random Forest (RandomForestClassifier)
   - AdaBoost (AdaBoostClassifier)
   - Extra Trees (ExtraTreesClassifier)
   - XGBoost (XGBClassifier)
   - LightGBM (LGBMClassifier)
   - Gradient Boosting (GradientBoostingClassifier)
5. **Performance Comparison**:
   - ML models were trained with QML embeddings and without embeddings.
   - Performance metrics computed:
     - Accuracy
     - Precision
     - Recall
     - F1 Score
     - ROC AUC
     - Cohen’s Kappa
     - Running Time (s)

## Results
The performance of canonical ML models with and without QML embeddings was compared to assess the potential advantages of QML embeddings in enhancing classical ML models.

## Installation & Dependencies
To set up the environment, install the necessary dependencies:
```bash
pip install pennylane scikit-learn numpy pandas
```

---
This project serves as an analysis of QML embeddings in classical ML pipelines and their impact on model performance. 🚀

