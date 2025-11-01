## 🔥 Fire Detection Using Deep Learning

A custom CNN-based Fire Detection System designed for real-time image classification. This model achieves 94% test accuracy, outperforming ResNet50 on the same dataset, while remaining lightweight and deployable via TensorFlow Lite.

---

## 🚀 Highlights

Frameworks: TensorFlow & Keras

Performance: 94% accuracy, superior to ResNet50 benchmark

Deployment: Optimized for real-time detection on edge devices

Tested on: Google Colab T4 GPU & local RTX 4060 GPU

---

## ⚙️ Features

Real-time fire vs. non-fire classification

Advanced data preprocessing & augmentation

Visualization through confusion matrix, accuracy, and loss curves

---

## 📸 Screenshots

![CNN_model_accuracy](https://github.com/user-attachments/assets/d5c022b8-023b-4d3d-a60d-6790b61e58a4)


![CNN_Confusion_Matrix](https://github.com/user-attachments/assets/02987653-ea30-4a65-8065-a7233ef19589)


---

## 📦 Future Scope

Integration with IoT devices and live video feed monitoring for smart safety systems.

---

## ⚙️ How to Run:

-Clone the repository

 git clone https://github.com/yourusername/fire-detection-cnn.git
 cd fire-detection-cnn


- Install dependencies

  pip install -r requirements.txt



- Train the model (optional if pretrained weights are included)

  python train.py


- Test or run real-time detection

  python detect.py --source path_to_image_or_video


- For TensorFlow Lite deployment, convert the model using the included script:

  python convert_to_tflite.py
