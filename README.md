# Activity-Recognition-CNN-LSTM

🚀 Overview
This project focuses on realistic human activity recognition from video sequences using a hybrid Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) architecture.

- CNN extracts spatial features from video frames.
- LSTM models the temporal dependencies across frames.
- Together, they enable robust recognition of dynamic human activities.

🧠 Key Features
- End-to-end pipeline for activity recognition from raw video.
- Preprocessing pipeline to resize and normalize frames.
- Frame-level feature extraction using CNN.
- Sequence modeling using LSTM.
- High training accuracy with minimal overfitting (with dropout & regularization).
- Visualizations for training accuracy, loss, and predictions.

⚙️ Tech Stack

- Language: Python 
- Deep Learning: TensorFlow / Keras
- Libraries: NumPy, OpenCV, Matplotlib, scikit-learn
- Dataset: Realistic Action Recognition: UCF50(https://www.kaggle.com/datasets/pypiahmad/realistic-action-recognition-ucf50)

📊 Results

- ✅ Training accuracy: ~98% (with stable loss curve)
- 📉 Test performance: achieved strong generalization
- 🔎 Visualization: includes confusion matrix and sample predictions

<img width="1048" height="313" alt="Screenshot 2025-09-02 230504" src="https://github.com/user-attachments/assets/b5991287-4c6e-485a-a47b-60255550e30c" />

