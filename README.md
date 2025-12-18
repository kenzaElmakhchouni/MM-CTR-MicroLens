# Multimodal CTR Prediction – MicroLens 1M

This project was developed for the **WWW 2025 Multimodal CTR (MM-CTR) Challenge**.

## Author & Affiliation
**Realized by:**  
**Kenza EL MAKHCHOUNI**  
Master’s student in **Big Data and Smart Systems**  
**Sidi Mohamed Ben Abdellah University (USMBA)**, Morocco

## Overview
This project presents an end-to-end **multimodal Click-Through Rate (CTR) prediction pipeline**
that leverages both textual and visual item information to improve recommendation accuracy.

The implementation follows the two official challenge tasks:
- **Task 1:** Multimodal item representation learning (text + image)
- **Task 2:** CTR prediction using deep neural networks

## Dataset
- **MicroLens-1M** dataset  
- Provided by **Westlake University** for the WWW 2025 MM-CTR Challenge

## Methodology
- **Text Encoding:** Sentence-BERT
- **Image Encoding:** CLIP (ResNet-50)
- **Multimodal Fusion:** Feature concatenation followed by PCA (128-dimensional embeddings)
- **CTR Model:** Deep MLP-based neural network optimized for binary classification

## Evaluation
- **Metric:** AUC (Area Under the ROC Curve)  
- **Validation AUC:** **0.92**

## How to Run
1. Open the provided notebook
2. Execute **Task 1** to generate multimodal item embeddings
3. Execute **Task 2** to train and validate the CTR prediction model
4. Generate `submission.csv` for challenge submission

## Notes
This project was developed for **educational, academic, and research purposes**, focusing on
reliable multimodal representation learning and CTR prediction for large-scale
recommendation systems, within the scope of the WWW 2025 MM-CTR Challenge.
