# Fashion-MNIST-Classifier

A simple neural network to classify clothing images from the **Fashion MNIST dataset** using **TensorFlow** and **Keras**.

---

## **Project Overview**

This project demonstrates a basic workflow of image classification using a neural network:

1. Load and preprocess the Fashion MNIST dataset.
2. Visualize sample images from each category.
3. Build a feedforward neural network with TensorFlow/Keras.
4. Train the model and evaluate its performance.
5. Plot training and validation accuracy and loss.

---

## **Features**

- Classifies 10 clothing categories:  
  `T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle Boot`
- Trains on 60,000 images and validates on 10,000 images.
- Visualizes sample images and training results.
- Lightweight and beginner-friendly code for understanding neural networks.

---

## **Installation**

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/Fashion-MNIST-Classifier.git
cd Fashion-MNIST-Classifier
pip install -r requirements.txt
from tensorflow.keras.datasets import fashion_mnist
(x_train, y_train), (x_test, y_test) = fashion_mnist.load_data()
python src/train_model.py
python src/evaluate_model.py
