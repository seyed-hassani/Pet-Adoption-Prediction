# Pet Adoption Prediction

This project builds a deep learning classifier using Keras to predict whether a pet listed for adoption will find a new home or not. The model is trained on pet metadata such as age, breed, color, health status, vaccination records, and more.

##  Goal

To accurately classify pets into "adopted" or "not adopted" based on structured data, using a binary classification neural network model.

##  Model Overview

- Framework: Keras (TensorFlow backend)
- Architecture: 3-layer Dense Neural Network (5000 → 1000 → 500 units)
- Activation: ReLU (hidden layers), Sigmoid (output)
- Loss: Binary Crossentropy
- Optimizer: Adam
- Evaluation Metric: Weighted F1 Score

##  Files

- `new_home.ipynb` – Jupyter notebook with full code
- `submission.csv` – Binary predictions for test set
- `test.csv` – Preprocessed test data
- `model_info.json` – Architecture details of the model
- `result.zip` – Compressed output for submission

##  Dataset

The dataset includes features like:
- Type, Age, Breed, Gender
- Colors, Size, Fur Length
- Vaccination, Sterilization, Health
- Fee, Photo Count
- Description (excluded for this model)

> Target: Whether the pet was adopted or not.

##  Requirements

```bash
pip install -r requirements.txt
