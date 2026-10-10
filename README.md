# DeepLearning_Applications

A collection of deep learning practice projects using publicly available datasets and benchmark problems. This repository explores neural networks, CNNs, transfer learning, and time-series forecasting using TensorFlow and Keras.

## Projects

### 1. Fashion MNIST
Build a multi-hidden-layer neural network using TensorFlow/Keras to classify 28×28 grayscale images into 10 clothing categories.

**References**
- [Fashion MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist)
- [TensorFlow: Basic Classification — Classify Images of Clothing](https://www.tensorflow.org/tutorials/keras/classification)

### 2. CNNs on CIFAR-10
Improve CNN image classification performance on CIFAR-10 by experimenting with batch normalization, data augmentation, and dropout.

**References**
- [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)
- [TensorFlow: CIFAR-10 Classification](https://www.tensorflow.org/tutorials/images/cnn)

### 3. Transfer Learning with ImageNet
Apply feature extraction and fine-tuning using pretrained ImageNet models to classify the TensorFlow Flowers dataset. Compare MobileNetV2 with another pretrained model from Keras Applications.

**References**
- [TensorFlow: Transfer Learning with TensorFlow Hub](https://www.tensorflow.org/tutorials/images/transfer_learning_with_hub)
- [TensorFlow: Transfer Learning and Fine-Tuning](https://www.tensorflow.org/tutorials/images/transfer_learning)
- [TensorFlow Flowers Dataset](https://www.tensorflow.org/tutorials/images/classification)

### 4. Pneumonia Detection
Develop a three-class image classification model to distinguish Normal, Bacterial, and Viral cases using transfer learning. Compare feature extraction and fine-tuning with different pretrained models.

**References**
- [Kaggle: Pneumonia Detection Competition](https://www.kaggle.com/competitions/pneumonia-detection/data)
- [TensorFlow: Transfer Learning with TensorFlow Hub](https://www.tensorflow.org/tutorials/images/transfer_learning_with_hub)
- [TensorFlow: Transfer Learning and Fine-Tuning](https://www.tensorflow.org/tutorials/images/transfer_learning)

### 5. Jena Climate Time Series Forecasting
Develop a data-windowing approach for multivariate, multi-step time-series forecasting using the Jena Climate dataset. Compare Dense, CNN, and RNN models using RMSE and R² scores.

**References**
- [TensorFlow: Time Series Forecasting](https://www.tensorflow.org/tutorials/structured_data/time_series)
- [Jena Climate Dataset](https://storage.googleapis.com/tensorflow/tf-keras-datasets/jena_climate_2009_2016.csv.zip)
