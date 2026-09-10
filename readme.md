# Waste Classification using Deep Learning

## Project Overview

This project is a deep learning-based waste classification system that classifies waste images into five categories:

- Glass
- Metal
- Organic
- Paper
- Plastic

The project compares a custom CNN model with two transfer learning models: MobileNetV2 and EfficientNetB0.

## Dataset

The dataset contains 3,875 images, with 775 images for each of the five classes.

The battery class was excluded because this project focuses on five waste categories.

## Models Used

1. Baseline CNN
2. MobileNetV2
3. EfficientNetB0

## Results

| Model | Test Accuracy |
|---|---:|
| Baseline CNN | 55.50% |
| MobileNetV2 | 79.73% |
| EfficientNetB0 | 92.61% |

EfficientNetB0 achieved the best performance with a test accuracy of 92.61% and a macro F1-score of 92.55%.

## Technologies

- Python
- TensorFlow / Keras
- Deep Learning
- Convolutional Neural Networks (CNN)
- Transfer Learning
- MobileNetV2
- EfficientNetB0
- Kaggle

## Conclusion

The results show that transfer learning significantly improved waste classification performance compared with the custom CNN. EfficientNetB0 was the best-performing model for this project.
