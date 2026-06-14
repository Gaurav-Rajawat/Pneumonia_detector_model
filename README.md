# Pneumonia Detector Model

## Overview
This project uses Deep Learning and Transfer Learning to detect Pneumonia from Chest X-ray images. The model is trained using TensorFlow and Keras and can classify X-ray images into:

- Normal
- Pneumonia

## Dataset
The dataset consists of chest X-ray images organized into training, validation, and test sets.

Dataset Structure:

```
dataset/
│
├── train/
│   ├── NORMAL/
│   └── PNEUMONIA/
│
├── val/
│   ├── NORMAL/
│   └── PNEUMONIA/
│
└── test/
    ├── NORMAL/
    └── PNEUMONIA/
```

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

## Model Architecture

- Transfer Learning
- Pretrained CNN Backbone
- Data Augmentation
- Binary Classification Output Layer

## Features

- Image preprocessing and normalization
- Data augmentation
- Transfer learning
- Model training and validation
- Performance evaluation
- Pneumonia prediction on unseen X-ray images

## Installation

Clone the repository:

```bash
git clone https://github.com/Gaurav-Rajawat/Pneumonia_detector_model.git
```

Install dependencies:

```bash
pip install tensorflow numpy matplotlib
```

## Usage

Open the notebook:

```bash
Pneumonia_detection.ipynb
```

Run all cells to:

1. Load dataset
2. Preprocess images
3. Train model
4. Evaluate performance
5. Make predictions

## Results

The model is trained to classify chest X-ray images as either Normal or Pneumonia. Performance metrics such as accuracy, loss, and confusion matrix can be used to evaluate the model.

## Future Improvements

- Fine-tuning pretrained layers
- Hyperparameter optimization
- Model deployment using Flask/FastAPI
- Multi-class lung disease classification

## Author

Gaurav Rajawat

## License

This project is open source and available under the MIT License.
