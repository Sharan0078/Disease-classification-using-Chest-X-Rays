# Chest-Xray-Multi-Disease-Classification

This project focuses on automatic detection of thoracic diseases from chest X-ray images using deep learning techniques.

Chest radiography is one of the most widely used medical imaging methods for diagnosing diseases affecting the lungs, heart, and surrounding thoracic structures. However, manual interpretation of X-rays can be difficult and time-consuming due to subtle visual patterns, large imaging volumes, and variability between radiologists.

The objective of this project is to build a multi-label image classification model capable of detecting multiple thoracic pathologies from chest X-ray images, including a **No Finding** category.

The model learns to identify disease-related visual features such as:
- Lung infections
- Pleural effusion
- Pulmonary edema
- Cardiomegaly
- Lung collapse and other thoracic abnormalities

Special attention was given to handling:
- Class imbalance across diseases
- Rare pathology detection
- Reduction of false negatives due to their high clinical impact

The training pipeline includes image preprocessing, augmentation, and deep learning–based classification techniques designed for robust medical image analysis.

## Dataset
The dataset used for this project is not included in this repository due to its large size.

Dataset Link:  
https://www.kaggle.com/competitions/26-t-1-dl-gen-ainppe-1/data

The dataset contains chest X-ray images along with binary labels for 20 thoracic pathology classes.

Please download the dataset from the Kaggle competition page before training or running the notebook.

## Key Features
- Multi-label chest X-ray classification
- Detection of 20 thoracic disease classes
- Handling of class imbalance
- Medical image augmentation techniques
- Deep learning–based diagnostic assistance
- False negative aware optimization

## Technologies Used
- Python
- PyTorch
- NumPy
- OpenCV
- Pandas
- Matplotlib
- Kaggle Notebooks

## Evaluation
The competition uses a macro-averaged asymmetric scoring metric where false negatives are penalized much more heavily than false positives, reflecting real-world clinical importance.

## Applications
- AI-assisted radiology
- Automated disease screening
- Clinical decision support systems
- Medical image analysis
- Healthcare AI research

This project demonstrates how deep learning models can assist in large-scale medical image interpretation and support faster, more reliable thoracic disease detection.
