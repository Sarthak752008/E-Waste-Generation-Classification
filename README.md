
# E-Waste Image Classification using EfficientNetV2B0

This project focuses on classifying images of electronic waste (e-waste) using transfer learning with the EfficientNetV2B0 model in a Jupyter notebook. It leverages a custom dataset of e-waste images and provides a step-by-step lab manual to help understand and implement the model.

## 📁 Project Structure

```

📦E-Waste-Classification/
┣ 📄E-Waste Generation Classification.ipynb
┣ 📄E-Waste Image Classification Using EfficientNetV2B0 (Transfer Learning) Lab Manual.pdf
┣ 📦E-Waste classification dataset.zip
┗ 📄README.md

````

---

## 🚀 Features

- Image classification using **EfficientNetV2B0** architecture.
- Utilizes **Transfer Learning** for improved accuracy and faster training.
- Dataset includes labeled e-waste images across multiple categories.
- Jupyter Notebook provides end-to-end workflow: data loading, preprocessing, model training, and evaluation.

---

## 📚 Requirements

Ensure the following Python packages are installed:

```bash
tensorflow
keras
matplotlib
numpy
pandas
scikit-learn
opencv-python
````

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## 🧠 Model Overview

The model used is **EfficientNetV2B0**, a modern convolutional neural network architecture optimized for both speed and accuracy. It is fine-tuned on the custom e-waste dataset for classification tasks.

---

## 📝 How to Run

1. **Unzip** the dataset:

   * Extract `E-Waste classification dataset.zip` into a folder.

2. **Open the notebook**:

   * Launch Jupyter Notebook or VS Code.
   * Open `E-Waste Generation Classification.ipynb`.

3. **Modify paths** (if needed):

   * Update any file paths to point to your extracted dataset folder.

4. **Run all cells**:

   * Step-by-step guidance and output will be displayed.
   * Includes data augmentation, training, validation, and accuracy visualization.

---

## 📊 Output

* Model training/validation accuracy and loss plots
* Classification metrics (accuracy, confusion matrix)
* Prediction samples

---

## 📘 Documentation

Please refer to the **Lab Manual PDF**:

> `E-Waste Image Classification Using EfficientNetV2B0 (Transfer Learning) Lab Manual.pdf`
> It contains detailed explanations, screenshots, and step-by-step instructions.

---

## 📦 Dataset

The dataset includes labeled images of various types of e-waste. Categories might include:

* Mobile Phones
* Keyboards
* PCBs (Printed Circuit Boards)
* Chargers
* Others

> Make sure the dataset is extracted and structured correctly before use.

---

## 🙌 Acknowledgements

* Model: [EfficientNetV2 by Google](https://arxiv.org/abs/2104.00298)
* Dataset: Custom collected or open source e-waste images
* Project developed for AICTE Internship / Educational Purpose

---

## 📌 Notes

* This project is intended for educational use only.
* For deployment, further model optimization and dataset validation are recommended.

