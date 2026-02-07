# DeepLearning_Model_Evaluators

This repository demonstrates how I **evaluate and test a Computer Vision (CV) face & gender detection model without a GPU**, using **Google Colab webcam integration**.

The project combines:
- **Haar Cascade Face Detection**
- **Custom Gender Detection Model (MobileNetV3 Small – V13)**

It is especially useful for users who **do not have a GPU-based PC** but still want to test deep learning models in real time.

---

## 🚀 Project Overview

- **Face Detection:**  
  Uses OpenCV’s `haarcascade_frontalface_default.xml` for real-time face detection.

- **Gender Classification:**  
  A custom-trained **MobileNetV3 Small** model (binary classification: Male / Female).

- **Platform:**  
  Google Colab (Webcam-based testing via JavaScript bridge).

---

## 🧠 Model Details

| Component | Description |
|---------|------------|
| Face Detector | Haar Cascade (OpenCV) |
| Gender Model | MobileNetV3 Small (V13) |
| Input Size | 224 × 224 |
| Output | Sigmoid (Male / Female) |
| Framework | TensorFlow / Keras |

---

## 📊 Results

### ✅ Accuracy
- **Face capture accuracy:** `75% – 95%`
- Works well for **single-face, front-facing detection**

### ⚠️ Known Issues
- Face tracking is **not perfectly smooth**
- Multiple face detection needs improvement
- Accuracy drops when the face is:
  - Too far from the camera
  - Partially visible
  - Poorly lit

---

## 🧪 Test Scenarios Covered

- [yes] Single face detection  
- [yes] Gender prediction  
- [yes] Multiple face detection (needs improvement)  
- [yes] Long-distance face detection  
- [yes] Face mismatch edge cases  

---

## 🛠 Installation (Google Colab)

Run the following command in Colab:

```bash
!pip install tensorflow opencv-python-headless pillow
```
The goal is that make it more perfect Model because testing work well........................ Thank you!
