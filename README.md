# 🐱🐶 Cats vs Dogs Image Classification

This project is an image classification model that identifies whether an image contains a **cat or a dog**.

## 🚀 Project Overview

The model is built using **Python and TensorFlow/Keras** and uses **MobileNetV2** with transfer learning to achieve accurate image classification.

The project includes:

- Automatic Cats vs Dogs dataset download
- Image validation and corrupted-image removal
- Training and validation dataset preparation
- Data augmentation
- Transfer learning using MobileNetV2
- Initial model training
- Fine-tuning of the pretrained model
- Training and validation accuracy graphs
- Training and validation loss graphs
- Model evaluation
- Sample image predictions with confidence scores
- Saving the trained model in `.keras` format

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Matplotlib
- PIL (Pillow)
- Google Colab

## 🧠 Model

The project uses **MobileNetV2 pretrained on ImageNet**.

The base model is initially frozen and trained with a new classification layer. After that, selected layers are unfrozen and the model is fine-tuned using a smaller learning rate.

## 📊 Output

The project produces:

- Training vs Validation Accuracy graph
- Training vs Validation Loss graph
- Final validation accuracy
- Sample predictions
- Prediction confidence scores

## ▶️ How to Run

1. Open the notebook in **Google Colab**.
2. Run the cells from beginning to end.
3. The dataset is downloaded automatically.
4. The model is trained and fine-tuned.
5. Accuracy and loss graphs are displayed.
6. Sample predictions are displayed.
7. The trained model is saved as:

```text
cats_vs_dogs_mobilenetv2.keras
