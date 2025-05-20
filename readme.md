# Parking Slot Image Classification

This project is a simple image classification model that detects **empty** and **non-empty** parking slots using machine learning. It leverages the **Support Vector Machine (SVM)** algorithm to classify parking space images based on whether they are vacant or occupied.

## 🧠 Model Overview

- **Model Type**: Image Classification
- **Algorithm**: Support Vector Classifier (SVC) with GridSearchCV for hyperparameter tuning
- **Libraries Used**: `scikit-learn`, `skimage`, `numpy`

## 📁 Dataset Structure

The dataset should be organized into two folders inside a directory named `clf-data`:

Each image is resized to 15x15 pixels and flattened into a 1D array before feeding into the model.

## ⚙️ How It Works

1. **Data Preprocessing**:

   - Loads images from `clf-data/empty` and `clf-data/not_empty`.
   - Resizes each image to 15x15 pixels.
   - Converts images into flat arrays.

2. **Model Training**:

   - Splits data into training and test sets (80/20).
   - Trains an SVM classifier using `GridSearchCV` to find the best hyperparameters (`C` and `gamma`).

3. **Evaluation**:
   - Makes predictions on the test set.
   - Outputs the classification accuracy.

## 🧪 Sample Output

_(The actual percentage will depend on your dataset.)_

## 🛠 Requirements

Make sure the following Python libraries are installed:

```bash
pip install numpy scikit-learn scikit-image


Running the Code

python your_script_name.py

Notes
Ensure your dataset images are of reasonable quality and consistent lighting for best results.

You can improve accuracy by experimenting with image size, feature extraction techniques, or using deep learning models.

📄 License
This project is open source and available under the MIT License.









```
