# Onion Health Classification

This project classifies onion images as healthy or unhealthy.

Original dataset file : https://drive.google.com/file/d/17qu2CPXT2CNHWj99JAVLXA2x9LCGlq2y/view?usp=sharing

## Models Used

- SimpleCNN
- ImprovedCNN
- MobileNetV3-Small
- Fine-tuned MobileNetV3-Small

## Dataset Workflow

The original dataset was divided into training, validation, and test sets.

Additional external onion images were used to fine-tune MobileNetV3-Small and evaluate its performance on unseen images.

## Evaluation Metrics

The project calculates:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix

## Notebook

The complete code is available in:

`onion_classification_project.ipynb`

