# Land Cover Classification with Machine Learning 🌍🛰️

This project implements a Land Cover (LC) classification workflow using Sentinel-2 satellite imagery and machine learning algorithms in Python. It aims to classify different land cover types (e.g., vegetation, water, urban, bare land) from multispectral satellite bands.

## 📂  Project Structure


## 🛰️ Input Data

- Sentinel-2 bands: B2, B3, B4, B8, B11, B12
- Labeled training data (shapefile or raster mask)
- Study area shapefile (optional)

## 🧠 Methods Used

- Preprocessing: Resampling, clipping, stacking bands
- Feature extraction: Spectral indices (e.g., NDVI, NDWI)
- Classification:
  - Random Forest (RF)
  - Support Vector Machine (SVM)
  - Optional: XGBoost, Decision Trees
- Accuracy assessment: Confusion matrix, accuracy, Kappa

## 🚀 How to Run


