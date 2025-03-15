# Lung_Disease_Classification

## Overview
This project is designed to classify lung X-ray images to determine whether a patient has COVID-19, normal lungs, or viral pneumonia. The model leverages deep learning techniques to analyze chest X-ray images and provide an automated diagnosis, assisting healthcare professionals in early detection and treatment.

## Dataset
The dataset used in this project consists of chest X-ray images categorized into three classes:
- **COVID-19**: X-ray images of lungs affected by COVID-19.
- **Normal**: Healthy lung X-ray images.
- **Viral Pneumonia**: X-ray images showing viral pneumonia infection.

## Features
- Preprocessing of X-ray images (resizing, normalization, and augmentation).
- Deep learning model (e.g., CNN) for image classification.
- Evaluation metrics such as accuracy, precision, recall, and confusion matrix.
- Visualization of model performance.

## Requirements
To run this project, install the necessary dependencies:
```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn
```

## Usage
1. Load the dataset and preprocess images.
2. Train the deep learning model using the provided notebook.
3. Evaluate the model's performance on test data.
4. Use the trained model to classify new X-ray images.

Run the Jupyter Notebook:
```bash
jupyter notebook Lung-Disease-Identification.ipynb
```

## Model Performance
The model's performance is evaluated using:
- **Accuracy**: Measures overall correctness.
- **Precision & Recall**: Evaluates class-specific performance.
- **F1-score**: Balances precision and recall.
- **Confusion Matrix**: Provides insights into misclassifications.

## Results
After training, the model achieves a reasonable classification performance. Fine-tuning hyperparameters, adding more data, and using advanced architectures (e.g., ResNet, EfficientNet) can improve accuracy.

## Future Improvements
- Enhance data augmentation techniques.
- Experiment with transfer learning.
- Optimize model architecture for better generalization.

## License
This project is MIT-Licensed and available for research and educational purposes.

## Acknowledgments
Special thanks to the creators of the dataset and the open-source community for making deep learning tools accessible.

