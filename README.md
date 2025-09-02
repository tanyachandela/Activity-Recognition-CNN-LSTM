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

- Training Accuracy: Achieved up to 98.5% by epoch 22.
-  Accuracy: Peaked at 81.4%, demonstrating strong generalization.
- Validation Loss: Minimum 0.631 at epoch 18 (best checkpoint saved).
- Early Stopping: Implemented to prevent overfitting; training stopped automatically when validation loss stopped improving.
- Stability: Learning rate scheduling ensured smooth convergence.

<img width="1048" height="313" alt="Screenshot 2025-09-02 230504" src="https://github.com/user-attachments/assets/b5991287-4c6e-485a-a47b-60255550e30c" />

✅ Conclusion

- This project successfully demonstrates the power of combining Convolutional Neural Networks (CNNs) with Long Short-Term Memory (LSTM) networks for realistic human activity recognition.
- CNNs efficiently extracted spatial features from the sensor data, while LSTMs modeled the temporal dependencies, leading to robust performance.
- The model achieved 98% training accuracy and around 81% validation accuracy, proving its effectiveness in recognizing complex real-world activities.
- With further fine-tuning, data augmentation, and larger datasets, this framework can be scaled for healthcare monitoring, fitness tracking, and smart surveillance systems.

