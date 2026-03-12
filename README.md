# Real vs Fake Face Detection using CNN

## 📌 Project Overview

This project focuses on detecting whether a face image is **Real or Fake** using a **Convolutional Neural Network (CNN)**.
The model is trained on image data and learns patterns that help distinguish between genuine human faces and artificially generated or manipulated faces.

This project demonstrates how **Deep Learning and Computer Vision** techniques can be used to identify fake images and improve digital security.

---

## 🎯 Objectives

* Build a **CNN model** for image classification.
* Classify images into two categories: **Real Face** and **Fake Face**.
* Apply **data augmentation** to improve model generalization.
* Train and evaluate the model using deep learning techniques.

---

## 🧠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* PIL (Python Imaging Library)
* Scikit-learn
* Jupyter Notebook

---

## 📂 Project Structure

```
Real-Fake-Face-Detection/
│
├── cnn_real_vs_fake_face_detection.ipynb   # Main notebook
├── dataset/                                # Image dataset
│   ├── real/
│   └── fake/
│
├── README.md                               # Project documentation
```

---

## 📊 Dataset

The dataset contains **two classes**:

1. **Real Faces**
2. **Fake Faces**

The images are used to train the CNN model to recognize patterns between authentic and manipulated facial images.

---

## ⚙️ Model Architecture

The CNN model includes:

* Convolutional Layers
* MaxPooling Layers
* Flatten Layer
* Dense Layers
* Dropout Layer

These layers help the model extract important features from the images and classify them correctly.

---

## 🔄 Data Preprocessing

Before training, the images undergo preprocessing steps such as:

* Image resizing
* Normalization
* Data augmentation

  * Rotation
  * Zoom
  * Horizontal flipping
  * Rescaling

This helps improve model accuracy and prevents overfitting.

---

## 🚀 Training the Model

The CNN model is trained using the following steps:

1. Import required libraries.
2. Load and preprocess the dataset.
3. Apply data augmentation.
4. Build the CNN architecture.
5. Compile the model.
6. Train the model using training data.
7. Evaluate the model performance.

---

## 📈 Model Evaluation

The model performance is evaluated using:

* Training Accuracy
* Validation Accuracy
* Loss Function

Graphs are plotted to visualize the training and validation results.

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```
git clone https://github.com/mohammedajmalkondambath-ux/CNN-PROJECT.git
```

### Step 2: Install Required Libraries

```
pip install tensorflow numpy matplotlib scikit-learn pillow
```

### Step 3: Run the Notebook

Open the Jupyter Notebook and run:

```
cnn_real_vs_fake_face_detection.ipynb
```

---

## 💡 Applications

This project can be used in:

* Deepfake detection
* Social media security
* Identity verification systems
* Digital forensics
* Fake content detection

---

## 📚 Future Improvements

* Use a **larger dataset** for better accuracy.
* Implement **Transfer Learning (ResNet / VGG / MobileNet)**.
* Deploy the model as a **web application**.
* Improve real-time detection using **OpenCV**.

---

## 👨‍💻 Author

**Mohammed Ajmal**

---

## ⭐ Conclusion

This project demonstrates how **Convolutional Neural Networks (CNN)** can effectively classify images and detect fake faces. With further improvements and larger datasets, this system can contribute to combating deepfake technologies and enhancing digital trust.
