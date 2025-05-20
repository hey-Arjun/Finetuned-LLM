# Fine-Tuned VGG16 for Image Classification

This project fine-tunes the VGG16 convolutional neural network model on a custom dataset using transfer learning. The notebook `Finetuned_vgg16.ipynb` includes steps for data preprocessing, model customization, training, and evaluation.

## 📁 Project Structure

├── Finetuned_vgg16.ipynb # Jupyter Notebook with all code for model training
├── dataset/ # (Not included) Your training and validation image dataset
└── README.md


## 🚀 Features

- Transfer learning with pre-trained VGG16 from ImageNet
- Fine-tuning final layers for better performance on custom data
- Data augmentation for improved generalization
- Training/validation accuracy tracking and evaluation

## 🔧 Requirements

Make sure you have the following installed:

- Python 3.7+
- TensorFlow 2.x
- NumPy
- Matplotlib
- scikit-learn
- Jupyter

You can install them using pip:

```bash
pip install tensorflow numpy matplotlib scikit-learn jupyter      
