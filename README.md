# 🖼️ Image Classification Model

This project focuses on developing a deep learning model for image classification using TensorFlow and Keras. The dataset is classified based on the folders of each class.

## 📌 Project Identity

- **Name:** Salsabila Rizka Maulidina  
- **Email:** a004xbm448@devacademy.id / salsaajadehhh@gmail.com  
- **ID Dicoding:** a004xbm448  

---

## 📖 Project Description

This notebook performs image classification model training with steps:

- Setting up a dataset from an image folder
- Using `ImageDataGenerator` for data augmentation
- Building a CNN model with Keras Sequential API
- Training the model using the training set
- Evaluate performance with accuracy metrics, confusion matrix, and classification report
- Visualization of results and model performance

---

## 🗂️ Data Folder Structure

Datasets are stored in the following structure:
```
data/
├── class_1/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
├── class_2/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
└── ...
```

---

## 🔧 Modeling Steps

1. **Import Library**
2. **Data Preparation**: Create image and label dataframes
3. **Augmentation and Preprocessing**: Data normalization and augmentation
4. **Model Architecture**: `Sequential` CNN with `Conv2D`, `MaxPooling2D`, `Dropout`, etc.
5. **Compilation and Training**: Using Adam optimizer and callbacks
6. **Model Evaluation**: Confusion matrix, classification report, and accuracy/loss visualization.
7. **Saving Model**: Save the model into SavedModel format and convert it into TFLite and TFJS.
8. **Interface**: Metest the model by using the image in the test data
---
