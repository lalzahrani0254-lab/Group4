# Wasl: Arabic Medical Sign Language Recognition System

## Team Members

- joud almalki
- leen alzahrani

## Project Overview

Wasl is a Computer Vision system designed to assist deaf patients in communicating with hospital reception staff by recognizing Arabic medical sign language gestures and translating them into meaningful medical terms.

## Problem Statement

Deaf patients often face communication barriers when interacting with hospital reception staff. This may lead to misunderstandings and delays in receiving healthcare services.

## Project Objective

To develop an AI-powered system capable of recognizing Arabic medical sign language gestures and converting them into understandable medical words such as pain, medicine, hospital, and pharmacy.

## Dataset

Dataset: KArSL-100 (RGB)

Selected Classes: 16 Medical Signs

Examples:

- Hospital
- Pharmacy
- Medicine
- Pain
- Fever
- X-Ray
- Blood Analysis
- Surgery

Dataset Statistics:

- Total Images: 33,701
- Total Samples: 672

## Data Preparation

The dataset was divided into:

- Training Set: 70%
- Validation Set: 15%
- Test Set: 15%

## Data Augmentation

Applied augmentation techniques:

- Rotation
- Brightness Adjustment
- Contrast Adjustment
- Translation (Shift)
- Gaussian Noise
- Gaussian Blur

## Model

- MobileNetV2
- Transfer Learning

## Training Configuration

- Image Size: 224 × 224
- Epochs: 10
- RGB Images

## Results

### Test Accuracy

99.93%

### Evaluation Metrics

- Precision ≈ 1.00
- Recall ≈ 1.00
- F1-Score ≈ 1.00

## Future Work

- Real-time video recognition
- Mobile application
- Deployment in healthcare facilities

## How to Run

1. Open the notebook in Google Colab.
2. Upload the dataset.
3. Run all notebook cells.
4. Train the model.
5. Test using images or camera input.

## Project Demo

The system predicts medical sign language gestures and displays the corresponding medical term with confidence score.
