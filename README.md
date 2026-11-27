# AI-Generated vs Real Image Detection

**AIEN302 Machine Learning: Term Project, Fall 2026–2027**
Cyprus International University

## Team

| Student No | Name |
|---|---|
| 22314265 | Maryam Ahmadi |
| 22214471 | Romina Sonboldoust |
| 22010507 | Amir Mohammadi |
| 22305913 | Oumaima Nakrimi |

## Project

Binary classification of images as **Real** or **AI-generated**, comparing classical machine learning models with deep learning models.

## Dataset

**MD-SynReal12K: A Multi-Domain Benchmark Dataset for AI-Generated and Authentic Image Forensics**

- Source: Mendeley Data, https://data.mendeley.com/datasets/pjd7shvdgr (DOI: 10.17632/pjd7shvdgr.1)
- Published: 2 November 2026
- Size: 12,000 images (6,000 real, 6,000 AI-generated)
- Domains: human faces, fauna and wildlife, structured objects
- Resolution: 512 × 512, RGB
- Splits: Train / Validation / Test
- Licence: CC BY 4.0

## Preprocessing

- Convert all images to one file format
- Resize to 224 × 224
- Normalize pixel values

## Models

- **K-NN**, **Naive Bayes** and **SVM** on hand-crafted features (colour histogram, HOG, FFT)
- **CNN** with transfer learning (ResNet50)
- **Hybrid CNN-SVM**

## Evaluation

- Accuracy, precision, recall, F1-score
- Confusion matrix
- Training and validation accuracy / loss curves
- Number of learnable parameters
- Hyperparameter optimization
