#  Image Recognition Using Convolutional Neural Networks (CNN)

This project demonstrates the implementation of a Convolutional Neural Network (CNN) for binary image classification to identify whether an image contains a **cat** or a **dog**. The project is implemented in Python using TensorFlow and Keras libraries and utilizes the Kaggle dataset for training and testing.

---

##  Project Overview

- **Goal:** Train a CNN model to classify images into two categories: cats and dogs.
- **Dataset:** [Cat and Dog Dataset from Kaggle](https://www.kaggle.com/datasets/tongpython/cat-and-dog)
- **Platform:** Google Colab for easy execution and GPU acceleration.

---

##  Technologies Used

- **Google Colab**: For a cloud-based Python development environment.
- **TensorFlow & Keras**: For building and training the CNN model.
- **Kaggle API**: To fetch datasets directly in Colab.
- **Matplotlib & Seaborn**: For visualizing images and data.

---

##  Project Workflow

###  Setting Up Kaggle API in Google Colab

1. Upload the `kaggle.json` file using the Colab file uploader.  
2. Configure Kaggle API with the following commands:
   ```python
   !mkdir -p ~/.kaggle/ && mv kaggle.json ~/.kaggle/ && chmod 600 ~/.kaggle/kaggle.json
