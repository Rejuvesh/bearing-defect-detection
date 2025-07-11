# bearing-defect-detection
# Bearing Defect Detection using ML and DL

This project focuses on predicting potential defects in industrial bearings using both supervised (XGBoost) and unsupervised (Autoencoder) techniques. The aim is to enable early fault detection and reduce machine downtime.

##  Tools Used
- Python
- Pandas, Numpy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- TensorFlow/Keras
- SMOTE (Imbalanced-learn)

##  Project Structure
- `EDA.ipynb` – Initial exploration of dataset and visualizations.
- `Preprocessing_FeatureEngineering.ipynb` – Data cleaning, scaling, encoding, SMOTE.
- `Modeling_XGBoost_Autoencoder.ipynb` – Training and evaluation of both models.
- `Bearing_Defect_Report.pdf` – Final summary report with insights and performance.
- `plots/` – Visualizations like confusion matrices and ROC curves.

##  Model Summary
| Model       | Accuracy | Recall (Defect) | ROC-AUC |
|-------------|----------|-----------------|---------|
| XGBoost     | 99%      | 0%              | 0.52    |
| Autoencoder | 94%      | 6%              | 0.53    |

##  Future Improvements
- Threshold tuning with domain expertise.
- Real-time data stream integration.
- Ensemble-based anomaly detection.



