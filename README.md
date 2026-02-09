# Handwritten Digit Recognition using Machine Learning

This project demonstrates a **Handwritten Digit Recognition system** built using Python and Machine Learning techniques.  
The model is trained to recognize digits (0–9) from grayscale handwritten images, similar to the MNIST dataset.

The repository includes:
- Model training
- Prediction visualization
- Correct vs incorrect prediction analysis

---

## 📌 Project Overview

Handwritten digit recognition is a classic machine learning and computer vision problem.  
In this project, we train a model to classify handwritten digits and visualize its predictions on test samples.

Key highlights:
- Uses image pixel data as input features
- Classifies digits from **0 to 9**
- Visualizes predictions with **green (correct)** and **red (incorrect)** labels

---

## 🧠 Dataset

- Dataset: **MNIST Handwritten Digits**
- Image size: **28 × 28 pixels**
- Color format: **Grayscale**
- Classes: **10 digits (0–9)**

---

## 🛠️ Technologies Used

- Python 🐍
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Project Workflow

1. **Load Dataset**
   - Import handwritten digit images and labels

2. **Data Preprocessing**
   - Normalize pixel values
   - Flatten images if required

3. **Model Training**
   - Train a classification model on training data

4. **Model Evaluation**
   - Predict on test data
   - Compare predicted vs actual labels

5. **Visualization**
   - Display sample handwritten digits
   - Highlight correct predictions in green
   - Highlight incorrect predictions in red

---

## 📊 Sample Outputs

### 🔹 Sample Handwritten Digits
Displays random handwritten digit images with their true labels.

### 🔹 Model Predictions
- **Green text** → Correct prediction  
- **Red text** → Incorrect prediction  

This helps in visually understanding where the model performs well and where it fails.

---

## 📁 Repository Structure
