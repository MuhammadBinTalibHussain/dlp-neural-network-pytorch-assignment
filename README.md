# DLP Neural Network PyTorch Assignment

This repository contains my Deep Learning assignment implemented using **Python and PyTorch**. The assignment covers neural network training, activation functions, gradient analysis, loss functions, optimizers, regularization, hyperparameter tuning, and final model evaluation.

## Dataset

This assignment uses the **Fashion-MNIST** dataset provided by Zalando Research.

Fashion-MNIST contains 70,000 grayscale images of size 28×28 divided into 10 classes: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, and Ankle boot. The official dataset contains 60,000 training images and 10,000 test images.

### Download Dataset

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/zalando-research/fashionmnist

The Kaggle dataset contains the CSV files used in this assignment, including:

* `fashion-mnist_train.csv`
* `fashion-mnist_test.csv`

## Project Structure

```text
dlp-neural-network-pytorch-assignment/
│
├── assignment.ipynb
├── README.md
├── fashion-mnist_train.csv
└── fashion-mnist_test.csv
```

> **Note:** The dataset files do not need to be uploaded to GitHub. Download them from Kaggle and place them in the same folder as the notebook/code.

## Requirements

Install the required Python libraries:

```bash
pip install torch torchvision numpy matplotlib scikit-learn pandas
```

## How to Run

### Method 1: Download the Dataset and Run

1. Download the Fashion-MNIST dataset from Kaggle.
2. Extract/download the CSV files.
3. Place `fashion-mnist_train.csv` and `fashion-mnist_test.csv` in the project folder.
4. Open `assignment.ipynb` in Jupyter Notebook or VS Code.
5. Run the cells from top to bottom.

### Method 2: Run Directly with Python

If the assignment is provided as a Python file, run:

```bash
python assignment.py
```

Make sure the dataset CSV files are in the same folder as the Python file.

## Main Work Covered

The assignment includes:

* MLP neural network implementation
* Different activation functions
* Gradient verification
* Vanishing gradient analysis
* Cross-Entropy and MSE comparison
* Optimizer comparison
* Bias and variance analysis
* L2 regularization
* L1 regularization
* Dropout
* Batch normalization
* Early stopping
* Data augmentation
* Training with more data
* Hyperparameter tuning
* Confusion matrix
* Precision, recall and F1-score
* Final test evaluation

## Final Results

| Result          |               Accuracy |
| --------------- | ---------------------: |
| Part 2 Baseline |                 83.59% |
| Tuned Model     |                 84.65% |
| Improvement     | 1.06 percentage points |

The tuned model improved the baseline accuracy from **83.59% to 84.65%**, giving an improvement of **1.06 percentage points**.

## Final Tuned Configuration

* Learning Rate: `0.001`
* Hidden Width: `512`
* Dropout Rate: `0.2`

## Final Test Performance

* Accuracy: **84.65%**
* Macro Precision: **0.8499**
* Macro Recall: **0.8465**
* Macro F1 Score: **0.8460**

## Tools and Libraries

* Python
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

## Dataset Source

Fashion-MNIST was created by Zalando Research and is available through Kaggle and the official Fashion-MNIST repository.
