
***

# MNIST Image Classification

This repository contains a Jupyter notebook that trains a neural network to classify handwritten digits from the MNIST dataset using PyTorch.


## Project overview

- Loads the MNIST dataset of 28×28 grayscale digit images (0–9).
- Applies basic preprocessing and converts images to PyTorch tensors.
- Builds a neural network model for image classification.
- Trains the model with a suitable loss function and optimizer.
- Evaluates accuracy on the test set and may visualize sample predictions.


<img width="1182" height="593" alt="Image" src="https://github.com/user-attachments/assets/90160b14-75a3-47f1-bc01-7ac6b13b3983" />

## Repository structure

- `MNIST_classification.ipynb` – Main notebook with data loading, model definition, training, and evaluation code.

## Requirements

- Python 3  
- PyTorch  
- torchvision  
- matplotlib  
- numpy  

Example installation:

```bash
pip install torch torchvision matplotlib numpy
```

## How to run

1. Clone the repository:
   ```bash
   git clone https://github.com/LakshithaSenavirathna/MNIST_image_classification.git
   cd MNIST_image_classification
   ```
2. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
3. Open `MNIST_classification.ipynb` and run all cells in order.

## Dataset

The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits, commonly used as a benchmark for image classification models.

