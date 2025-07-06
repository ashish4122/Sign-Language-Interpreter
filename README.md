# 🧠 Sign Language Interpreter using Deep Learning

A real-time ASL interpreter using webcam input and a CNN model to recognize 44 American Sign Language gestures with over 95% accuracy.

---

## 🚀 Tech Stack

**Languages & Libraries**: Python, TensorFlow, Keras, OpenCV  
**Others**: NumPy, Pandas, Matplotlib

---


## 🛠️ How It Works

1. **Set Hand Histogram**  
   `python set_hand_histogram.py`

2. **Create and Label Gestures**  
   `python create_gestures.py`

3. **Augment Data**  
   `python Rotate_images.py`

4. **Split Dataset**  
   `python load_images.py`

5. **Train Model**  
   `python cnn_model_train.py`

6. **Run Live Recognition**  
   `python final.py`

---

## 🧠 Model Overview

- CNN with 3 Conv2D + MaxPooling layers
- Final Dense layers with softmax for classification
- Trained with SGD optimizer and categorical crossentropy

---

## ✅ Features

- Real-time sign recognition from webcam
- >95% accuracy on 44 ASL gestures
- Custom dataset creation and augmentation
- Modular pipeline with clear training & inference flow

---

## 📌 Future Improvements

- Cloud deployment with API access  
- Support for additional sign languages  
- Real-time feedback loop for learning  




