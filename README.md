# 🌸🌻🌹 Multi-Class Image Classification 🌼🌷
💥 **Computer Vision Project** 💥
## 🌼 Flower Recognition Project 🌼

This project implements a comprehensive workflow for flower recognition using a combination of traditional and deep learning techniques.

## 📂 Dataset

The flower recognition dataset (`tf_flowers`) is loaded from TensorFlow Datasets. It contains images of five types of flowers: 🌼 daisies, 🌷 tulips, 🌻 sunflowers, 🌾 dandelions, and 🌹 roses.

## 🛠️ Steps

### 1️⃣ Load Flower Recognition Dataset
We load and split the dataset into training and testing sets.

### 2️⃣ Count Classes and Images
We count the number of classes and examples in the training and test sets, and plot the class distribution.

### 3️⃣ Data Augmentation and Preprocessing
Images are augmented (rotated, flipped, resized) and preprocessed (normalized, converted to grayscale, histogram equalization, and denoised).

### 4️⃣ Feature Extraction
We extract three types of features from each image:
- **HOG Features**: Describes the structure and appearance of the images.
- **LBP Features**: Captures texture information.
- **CNN Features**: Extracted using a pre-trained VGG16 model.

### 5️⃣ Dimensionality Reduction
Features are reduced using:
- **PCA (Principal Component Analysis)**
- **LDA (Linear Discriminant Analysis)**
- **ICA (Independent Component Analysis)**

### 6️⃣ Classification
We train RandomForest and SVM classifiers on the reduced feature sets (PCA, LDA, ICA) and evaluate their performance using accuracy, precision, recall, and F1-score.

## 📊 Results Visualization
Results are visualized using bar plots to compare the performance of different dimensionality reduction techniques and SVM kernels.

## 📋 Requirements

- 🐍 Python 3.x
- 🤖 TensorFlow
- 📚 TensorFlow Datasets
- 📷 OpenCV
- 🖼️ scikit-image
- 📈 scikit-learn
- 📊 Matplotlib
- 🔢 NumPy

## 🚀 How to Run

1. 📥 Clone this repository.
2. 📦 Install the required libraries.
3. ▶️ Run the main script to execute the workflow.

## 🏆 Conclusion
This project demonstrates an effective pipeline for flower recognition using a combination of traditional image processing techniques and deep learning models. The results indicate that the choice of dimensionality reduction technique and classifier significantly impacts the performance of the model.

## 📄 License
This project is licensed under the MIT License.

```bash
Made with 💖 by Hamza Sajjad.
```
