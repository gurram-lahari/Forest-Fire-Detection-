# 🌲🔥 Forest Fire Detection using CNN

This project detects forest fires from images using Convolutional Neural Networks (CNN). It is a deep learning-based image classification system that distinguishes between fire and non-fire images, supporting early detection of wildfires to reduce damage and protect the environment.

## 🔍 Project Overview

- **Goal:** Binary classification of images into `Fire` and `No Fire`.
- **Dataset:** Collected from [Kaggle](https://www.kaggle.com/) – Wildfire Image Dataset.
- **Framework:** TensorFlow/Keras for building and training the CNN model.
- **Application:** Can be used in real-time monitoring systems for fire-prone regions.

---

## 🧠 Deep Learning Concepts Used

| Task                        | Method                                     |
|----------------------------|--------------------------------------------|
| Processing visual data     | Convolutional Neural Networks (CNN)        |
| Image classification       | Supervised learning (Binary classification)|
| Vision-based AI detection  | Roboflow + YOLO (alternative/extension)    |

> 🔧 **Note:** While YOLO is often used for object detection, this project focuses on image classification using CNN. YOLO integration can be done in future versions for real-time video surveillance.

---

## 🧪 Tools & Technologies

- Python
- TensorFlow / Keras
- OpenCV
- NumPy / Pandas
- Matplotlib / Seaborn
- Roboflow (for dataset visualization or deployment, optional)

---

## 📈 Project Pipeline

1. **Data Collection & Loading**
   - Dataset from Kaggle: fire and non-fire images.
   - Binary classification task.
   - Ensure all images are resized to the same dimensions (e.g., 224x224).

2. **Image Preprocessing & Augmentation**
   - Resize, normalize, and convert images to arrays.
   - Augment data (flip, rotate, zoom) using `ImageDataGenerator`.

3. **Model Building**
   - Construct a CNN using TensorFlow/Keras.
   - Input layer → Convolutional layers → MaxPooling → Dense layers → Output layer with sigmoid.

4. **Model Training**
   - Train the model on the preprocessed dataset.
   - Use validation split for performance monitoring.
   - Evaluate accuracy and loss using graphs.

5. **Testing & Deployment**
   - Test model on unseen images.
   - Optional: Deploy using Flask or Streamlit.



