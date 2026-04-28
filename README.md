# 😊 Face Emotion Detection System

## 📌 Overview

The **Face Emotion Detection System** is a deep learning-based project that detects human emotions from facial expressions in real-time. It uses a Convolutional Neural Network (CNN) trained on facial image data to classify emotions such as happiness, sadness, anger, surprise, and more.

This project is developed as a **Final Year B.Tech (CSE) Project**.

---

## 🚀 Features

* 🎯 Real-time face detection using webcam
* 🧠 Emotion classification using CNN model
* 📷 Image-based emotion prediction
* ⚡ Fast and efficient processing
* 📊 Trained on FER2013 dataset

---

## 🛠️ Tech Stack

* **Programming Language:** Python 3.10
* **Libraries & Frameworks:**

  * TensorFlow / Keras
  * OpenCV
  * NumPy
  * Pandas
  * Matplotlib
  * Scikit-learn

---

## 📂 Dataset

* **FER2013 Dataset**

  * Contains 48x48 grayscale facial images
  * 7 emotion classes:

    * Angry 😠
    * Disgust 🤢
    * Fear 😨
    * Happy 😄
    * Sad 😢
    * Surprise 😲
    * Neutral 😐

---

## 🧠 Model Architecture

* Convolutional Neural Network (CNN)
* Multiple Conv2D + MaxPooling layers
* Fully Connected Dense layers
* Activation: ReLU, Softmax
* Loss Function: Categorical Crossentropy
* Optimizer: Adam

---

## 📁 Project Structure

```
Face-Emotion-Detection/
│
├── dataset/
├── model/
│   ├── emotiondetector.json
│   └── emotiondetector.h5
│
├── train.py
├── predict.py
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Face-Emotion-Detection.git
cd Face-Emotion-Detection
```

### 2️⃣ Create virtual environment (recommended)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

### 🔹 Train the model

```bash
python train.py
```

### 🔹 Run emotion detection (webcam)

```bash
python app.py
```

### 🔹 Predict emotion from image

```bash
python predict.py
```

---

## 📊 Results

* Achieved accuracy: **~60–70%** (depends on training epochs and tuning)
* Performance can be improved using:

  * Data augmentation
  * Hyperparameter tuning
  * Transfer learning

---

## 📸 Output

* Detects face in real-time
* Displays predicted emotion label on screen

---

## ⚠️ Challenges

* FER2013 dataset is noisy and low-resolution
* Real-time detection may vary with lighting conditions
* Overfitting issues during training

---

## 🔮 Future Improvements

* Improve accuracy using pretrained models (ResNet, VGG)
* Deploy as a web application
* Add emotion-based recommendations
* Mobile app integration

---

## 👨‍💻 Author

* Amit Rawat
* B.Tech CSE Final Year Student

---

## 📜 License

This project is for educational purposes only.

---

## ⭐ Acknowledgements

* FER2013 Dataset
* TensorFlow & OpenCV communities

---
