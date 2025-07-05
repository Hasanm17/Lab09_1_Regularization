# Lab09_1_Regularization
Cats vs Dogs Regularization Techniques for CNN Classification

## Overview
This lab experiments with various regularization and data augmentation techniques to improve CNN performance on the Dogs vs. Cats dataset.

## Techniques Tested
- **Dropout Regularization** (0.3 and 0.5 rates)
- **L2 Weight Regularization** (λ=0.001)
- **Early Stopping** (patience=3)
- **Data Augmentation** (rotation, shifts, flip, zoom)
- **Combined Methods**

## Requirements
```bash
tensorflow>=2.0
numpy
matplotlib
pandas
seaborn
scikit-learn
```

## Usage
Run each section sequentially:
1. Data preparation and baseline model
2. Regularization experiments (dropout, L2, combined)
3. Early stopping and data augmentation
4. Results evaluation and comparison

## Key Results
- **Best Model**: Early Stopping (51.26% validation accuracy)
- **Best Overfitting Control**: L2 Regularization (87% gap reduction)
- **Best Generalization**: Data Augmentation (negative overfitting gaps)

## Dataset
Dogs vs. Cats dataset with 25,000 images split into 20,000 training and 5,000 validation samples.

## Author
Hasan Mairaj - Robotics Program
