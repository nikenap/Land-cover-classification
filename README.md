# Land-cover-classification

## Project Description
This code is part of a portfolio project aimed at understanding machine learning. It showcases a Python-based approach to land cover classification, utilizing Sentinel-2A satellite data. The process includes selecting relevant spectral bands (e.g., RGB and NIR) and incorporating vegetation indices such as the Normalized Difference Vegetation Index (NDVI) to enhance predictive accuracy. A Random Forest classifier is used to train the model on labeled data, and its performance is evaluated using metrics like accuracy and a confusion matrix. A detailed explanation is provided in this article.

## File
1. **landcover_classification.ipynb.**: Contains the Python code for data preprocessing, feature extraction, model training, and land cover classification.
2. **s2images**:A multi-band GeoTIFF file containing the Sentinel-2A imagery used for analysis. This file includes the RGB, NIR, and NDVI bands used in the classification process.
3. **lc.json**: A configuration file that stores the land cover classification scheme, including class labels and corresponding color codes for visualization.
4. **points.geojson**:A GeoJSON file containing labeled point data used as training and validation samples for the land cover classification model.

## Content
1. **Data Acquisition and Preprocessing:** Collecting and preparing satellite imagery for analysis.
2. **Feature Extraction and Training/Test Data Preparation:** Extracting relevant features and splitting data into training and testing sets.
3. **Model Training and Accuracy Assessment:** Building a machine learning model to classify land cover types and evaluating its performance.
4. **Prediction and Exporting Result:** Applying the model for predictions and exporting results for further use.

## Acknowledgement
This article is made possible thanks to the incredible support of the following open-source contributions:
1. [Ramadhan](https://github.com/ramiqcom/remote-sensing-python/blob/master/scripts/landcover_classification/landcover_classification.ipynb)
