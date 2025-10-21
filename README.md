# 3D-UNetPlusPlus-Modified-Pipeline

This repository contains the implementation and full workflow of our AI-based CMRI pipeline, submitted with the manuscript:

> **"From an Advanced AI-Based CMRI Segmentation to Classification: A Modified UNet++ and Feature Extraction Pipeline for Cardiac Diseases’ Diagnosis"**  
> (*PeerJ Computer Science, 2025*)

---

##  Overview
This project provides a reproducible implementation of a hierarchical deep learning framework for **cardiac cine-MRI segmentation and disease classification** using a modified **3D UNet++** architecture and quantitative feature extraction.

---

##  Content
- `ACDC_Preprocessing.ipynb` → Image normalization, resampling, and augmentation of the ACDC dataset  
- `ACDC_Model_Segmentation.ipynb` → 3D UNet++ segmentation model (training and inference)  
- `feature_extraction_and_classification.ipynb` → Feature extraction and disease classification  

---

##  Dataset Information
The dataset used in this study is the publicly available **Automated Cardiac Diagnosis Challenge (ACDC)** dataset, accessible at:  
 [https://www.creatis.insa-lyon.fr/Challenge/acdc/](https://www.creatis.insa-lyon.fr/Challenge/acdc/)

---

##  Requirements
```bash
Python >= 3.8  
TensorFlow >= 2.9  
Keras >= 2.9  
SimpleITK  
Nibabel  
NumPy  
Pandas  
Matplotlib  
scikit-learn  
