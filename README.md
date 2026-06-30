# PRODIGY_ML_04
# Hand Gesture Recognition - SVM

## Overview
A Support Vector Machine model to classify 10 different hand gestures using HOG features, enabling intuitive human-computer interaction.

## Dataset
LeapGestRecog dataset - 2000 images across 10 gesture classes

## Gesture Classes
- Palm, L-shape, Fist, Fist Moved, Thumb
- Index, OK, Palm Moved, C-shape, Down

## Approach
- Image preprocessing with OpenCV
- HOG feature extraction (1764 features per image)
- SVM with RBF kernel for classification

## Results
- Accuracy: 100%

## Libraries Used
- numpy, matplotlib, scikit-learn, scikit-image, opencv
