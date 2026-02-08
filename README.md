🩺 Breast Cancer Detection from Ultrasound Images

This project uses deep learning and image processing to automatically detect the presence of breast cancer from ultrasound images.

We trained the model using the **Breast Ultrasound Images Dataset (BUSI)** available on Kaggle.  
The dataset contains three categories:
- Benign
- Malignant
- Normal

For this project, **benign and malignant images are grouped as “Cancer Detected”**, while **normal images are treated as “No Cancer Detected.”**

---

### 🧠 Data Preprocessing
Before training, the following preprocessing steps were applied:
- Image resizing to 128×128
- RGB color conversion
- Pixel normalization
- Data augmentation (rotation, flipping, zooming, shifting)

These steps help improve model accuracy and generalization.

---

### 🤖 Model Architecture
A **Convolutional Neural Network (CNN)** was built using:
- 3 Convolution layers
- Max Pooling
- Dropout for regularization
- Sigmoid activation for binary classification

The model learns important image features such as tissue texture, shape, and intensity patterns.

---

### 📊 Model Performance
The trained CNN achieved good accuracy on test data, demonstrating its ability to distinguish between cancerous and non-cancerous ultrasound images.

---

### 🖥️ User Interface
A **Gradio web interface** is integrated with the model.

Users can:
- Upload a breast ultrasound image
- Instantly receive a prediction:
  - 🩺 Cancer Detected  
  - ✅ No Cancer Detected

---

### ⚠️ Disclaimer
This project is intended for **educational and research purposes only**.  
It is **not a substitute for professional medical diagnosis**.

---

### 📁 Dataset Source
- Breast Ultrasound Images Dataset (BUSI)
- Source: Kaggle
