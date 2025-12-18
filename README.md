# Multimodal CTR Prediction – MicroLens 1M

This project was developed for the WWW 2025 MM-CTR Challenge.

## Overview
We implement an end-to-end multimodal CTR prediction pipeline:
- Task 1: Multimodal item embedding (text + image)
- Task 2: CTR prediction using neural networks

## Dataset
MicroLens-1M dataset provided by Westlake University.

## Method
- Text encoding: Sentence-BERT
- Image encoding: CLIP (RN50)
- Fusion: Concatenation + PCA (128-d)
- CTR Model: MLP-based neural network

## Evaluation
Metric: AUC  
Validation AUC: **0.92**

## Project Pipeline
![Challenge's Task 1 Pipeline](MM-CTR_Task1_Architecture.png)
![Challenge's Task 2 Pipeline](MM-CTR_Task2_Architecture.png)

## How to Run
1. Open the notebook
2. Run Task 1
3. Run Task 2
4. Generate submission.csv
