# Cat vs Dog Image Classification

A deep learning project that classifies images as **Cat** or **Dog** using a **Convolutional Neural Network (CNN)** built with **PyTorch**.

## Project Overview

The images are resized to 128 × 128 pixels and preprocessed before being used for training.

The dataset is divided into:
- 80% Training
- 20% Testing

The trained model is evaluated using accuracy, precision, recall, and a confusion matrix.

## Technologies Used

- Python
- PyTorch
- Torchvision
- Scikit-learn
- CNN
- Jupyter Notebook

## CNN Architecture

The model consists of:
- 3 Convolutional layers
- ReLU activation
- Max Pooling
- Fully Connected layers
- Cross-Entropy Loss
- Adam Optimizer

## Dataset

[Kaggle - Dog and Cat Classification Dataset](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)

## How to Run

1. Clone this repository.
2. Download the dataset from Kaggle.
3. Place the `PetImages` folder in the project directory.
4. Open `cat_vs_dog.ipynb`.
5. Run the notebook cells sequentially.

## Project Structure

```text
cat-vs-dog-image-classification/
│
├── cat_vs_dog.ipynb
├── README.md
└── PetImages/
    ├── Cat/
    └── Dog/
```

## Author

**Chetan Kallappa Ingali**
