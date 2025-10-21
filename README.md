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





## Usage Instructions

Clone or download this repository.

Place the ACDC dataset in the /Dataset folder.

Run ACDC_Preprocessing.ipynb to normalize and resample images.

Run ACDC_Model_Segmentation.ipynb to train or test the 3D UNet++ segmentation model.

Run feature_extraction_and_classification.ipynb to extract features and classify cardiac diseases.

## Methodology

The pipeline follows the stages described in the manuscript:

Preprocessing: Normalization, resampling, and augmentation of cine-MRI data.

Segmentation: Lightweight 3D UNet++ model for LV/RV/MYO segmentation.

Feature Extraction: Quantitative LV, RV, and MYO measurements (volumes, ratios, contraction indices).

Classification: Disease classification into NOR, DCM, HCM, MINF, and RV abnormality groups.

## Citations

If you use this repository, please cite:

Alshehri A., Alqaissi E., Mabrouk B., Hammami R., Ben Hmida A.
From an Advanced AI-Based CMRI Segmentation to Classification: A Modified UNet++ and Feature Extraction Pipeline for Cardiac Diseases’ Diagnosis.
PeerJ Computer Science (2025).

Dataset citation:

Bernard O. et al., "Deep Learning Techniques for Automatic MRI Cardiac Segmentation and Diagnosis: The ACDC Challenge," Medical Image Analysis, 2018.

## License

This repository is released for academic and research purposes under a
Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)
🔗 https://creativecommons.org/licenses/by-nc/4.0/
