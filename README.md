# Deep Learning Project

A learning repository for deep learning models and practical implementations in Python. This repo currently includes hands-on notebooks for Artificial Neural Networks (ANN) and will expand to cover other foundational deep learning architectures.

## Repository Structure

- `ANN/`
  - `main.ipynb` – ANN implementation for customer churn prediction.
  - `requirements.txt` – dependencies for the ANN notebook.
  - `dataset/Churn_Modelling.csv` – dataset used in the ANN example.
- `DL Course Materials/`
  - `Part 1 - Artificial Neural Networks (ANN)/`
  - `Part 2 - Convolutional Neural Networks (CNN)/`
  - `Part 3 - Recurrent Neural Networks (RNN)/`
  - `Part 4 - Self Organizing Maps (SOM)/`
  - `Part 5 - Boltzmann Machines (BM)/`
  - `Part 6 - AutoEncoders (AE)/`
  - `Template for Data Preprocessing/`
  - `Template for Logistic Regression/`

## Current Contents

- ANN implementation with TensorFlow/Keras.
- Data preprocessing and encoding examples using pandas and scikit-learn.
- Training, prediction, and evaluation workflow for binary classification.

## Installation

Recommend using a Python 3.11 virtual environment.

```powershell
py -3.11 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip setuptools wheel
python -m pip install -r ANN/requirements.txt
```

## How to Use

1. Open `ANN/main.ipynb` in Jupyter or VS Code.
2. Run cells sequentially from data loading through model training and evaluation.
3. Update or extend notebooks for new datasets and model experiments.

## Future Additions

This repository will be expanded with:

- Convolutional Neural Network (CNN) examples
- Recurrent Neural Network (RNN) examples
- Self Organizing Map (SOM) examples
- Boltzmann Machine (BM) examples
- Autoencoder examples
- Additional datasets, model comparisons, and evaluation metrics

## Notes

- Keep dataset file paths relative to the notebook location.
- Use consistent Python environments to avoid dependency mismatch.
- Add README subsections as new notebooks and examples are added.
