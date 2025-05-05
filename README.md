Sign Speaks 🤟📢

**Sign Speaks** is a real-time sign language recognition system that translates Indian Sign Language (ISL) gestures into text using deep learning. This project is aimed at bridging the communication gap for individuals with hearing or speech impairments.

---

## 📌 Project Flow

1. **Data Collection**  
   Collect hand, face, and pose landmark data using the `Data Collection Final.ipynb` file. This uses Mediapipe and OpenCV to capture landmarks and save them as `.npy` files.

2. **Data Preprocessing & Model Training**  
   Use the `CNN working.ipynb` notebook to preprocess the collected data, build the Conv1D + LSTM model, and train it.

3. **Run & Test the Model**  
   Use `run file.ipynb` to load the trained model and perform real-time sign detection using your webcam.

---

## 💡 Features

- Real-time ISL sign recognition
- Lightweight and fast (CPU compatible)
- Easy to extend with new signs
- Built using Jupyter Notebooks for flexibility

---

## 🛠️ Tech Stack

- **Language:** Python 3.9  
- **Libraries:**  
  - OpenCV 4.10.0  
  - Mediapipe 0.10.20  
  - NumPy 1.23.5  
  - TensorFlow 2.12.0  
  - Scikit-learn 1.6.0  
  - SciPy 1.13.1

---
