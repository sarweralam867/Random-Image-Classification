# Random-Image-Classification
Image Classification || Brac University || CSE428 : Image Processing

## Project Overview
This project is part of the **CSE428: Image Processing** course at BRAC University. It involves using deep learning models for image classification on a custom dataset. The project compares the performance of several established neural network architectures and a custom model.

## Models Used
- **AlexNet**: A foundational CNN model for image classification.
- **ResNet-50**: Employs residual connections to handle deep network training effectively.
- **InceptionNet**: Uses inception modules for efficient multi-scale feature extraction.
- **Custom Model**: A custom-built, inception-inspired model designed to improve classification accuracy.

## Dataset
- **Size**: 2150 images for training, 250 images for testing.
- **Image Dimensions**: 64x64x3 (RGB).
- **Format**: Images were converted to CSV format for processing.
- **Partitioning**: The dataset was split into 80% training and 20% validation.

## Data Augmentation
Data augmentation was applied to enhance model robustness, including techniques such as random rotation, flips, and scaling, to prevent overfitting.

## Evaluation Metrics
Models were evaluated on:
- **Accuracy**: Overall correctness of predictions.
- **Precision**: Accuracy of positive predictions.
- **Recall**: Model's ability to identify all relevant instances.
- **Specificity**: Ability to correctly identify negative instances.

## Results
- **Best Performance**: The custom model achieved the highest accuracy, outperforming the pre-trained architectures.
- **Accuracy Comparison**: ResNet-50 and InceptionNet showed strong performance, with the custom model slightly outperforming them.

## Visualizations
Plots of training and validation accuracy/loss were used to monitor model performance over epochs. Confusion matrices highlight classification accuracy and errors for each model.

## Conclusion
This project demonstrates the efficacy of deep learning architectures in image classification tasks. Through model customization and comparison, we observed significant improvements in accuracy, especially with the custom model.

## Authors
This project was a group project BRAC University as part of the CSE428 course requirements.

## Acknowledgments
Thanks to BRAC University faculty and the CSE428 course team for their guidance.

