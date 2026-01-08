# 🐾 Cats vs Dogs Image Classification (Custom CNN Architecture)

This repository contains a **Custom Convolutional Neural Network (CNN)** built from scratch to classify images of cats and dogs with high precision.


##  Project Overview
The goal of this project was to design a robust deep learning model capable of distinguishing between feline and canine features. Unlike standard pre-trained models, this project features a **Custom Architecture** developed to optimize learning on the Kaggle "Dogs vs. Cats" dataset.

###  Key Highlights:
* **Custom CNN Design:** Hand-picked layers for feature extraction and spatial reduction.
* **Image Preprocessing:** Used grayscale/RGB normalization and resizing for uniform input.
* **Overfitting Control:** Implemented Dropout layers to ensure the model generalizes well on new data.
* **Efficiency:** Designed to be lightweight yet powerful for faster training.

---

## Custom Architecture Breakdown
The model follows a strategic sequence of layers designed during our collaborative development:

1.  **Input Layer:** Standardized image input (e.g., 64x64 or 128x128).
2.  **Convolutional Layers (Conv2D):** Multiple layers with increasing filters to capture complex patterns like fur texture, ear shapes, and snout structure.
3.  **Activation (ReLU):** Introduced non-linearity to help the model learn complex relationships.
4.  **Max Pooling:** Down-sampled the feature maps to reduce computational load and retain the most important information.
5.  **Dropout:** Added to prevent the model from "memorizing" the training data.
6.  **Flattening:** Converted the 2D spatial data into a 1D vector.
7.  **Fully Connected (Dense) Layers:** Interpreted the extracted features to make the final prediction.





##  Technology Stack
* **Language:** Python 3.x
* **Framework:** TensorFlow / Keras
* **Numerical Processing:** NumPy & Pandas
* **Data Visualization:** Matplotlib & Seaborn
* **Image Handling:** OpenCV


## Performance & Results
By fine-tuning the **Custom Architecture**, we achieved:
* **Stable Training:** Balanced accuracy between training and validation sets.
* **Visual Insights:** The model successfully identifies key distinguishing features of cats vs. dogs.



##  Practical Application (The "Mazdoor" Vision)
This custom classification logic serves as a foundation for my upcoming **Mazdoor App**. The same CNN principles will be applied to:
* **Identity Verification:** Ensuring users upload authentic profile pictures.
* **Automated Document Sorting:** Detecting and verifying CNIC/ID cards during registration.


**Developed  Intellectual Honesty.**
