## 📘 Overview
This project explores the use of **Machine Learning (ML)** techniques to predict **ICU length of stay (LOS)** using **Electronic Health Records (EHR)**.  
The goal is to classify patients into **short-stay** and **long-stay** categories to improve **patient care**, **resource allocation**, and **hospital efficiency**.

The study compares several ML algorithms — **Random Forest**, **XGBoost**, **Logistic Regression**, and **K-Nearest Neighbors (KNN)** and also conducts time series based approach using deep learning model**LSTM model**

## 🧾 Dataset
- **Source:** [MIMIC-IV v3.1](https://physionet.org/content/mimiciv/3.1/) (MIT Laboratory for Computational Physiology)  
- **Access:** Requires credentialed access via [PhysioNet](https://physionet.org/)  
- **Data Type:** De-identified EHR data of ICU patients  
- **Key Attributes:** Demographics, vital signs, lab tests, comorbidities, interventions, outcomes  
- **Target Variable:** ICU Length of Stay (Short vs. Long)

**Note:**   
> The **MIMIC-IV dataset** requires credentialed access from [PhysioNet](https://physionet.org/). Only the **code files** with no PHI data are uploaded to this GitHub repository.
