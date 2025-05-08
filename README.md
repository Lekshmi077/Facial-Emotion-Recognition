# Facial Emotion Recognition with Deep Residual Learning

This project uses a custom deep residual CNN (ResNet-inspired) to classify facial expressions into **Happy, Neutral, and Sadness** using grayscale facial images.

## 📁 Dataset
- Combined dataset: FER2013 (aligned) + CK+
- Images are grayscale, 48x48

## 🔧 Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab (training)

## 📈 Model Architecture
- Custom Residual CNN
- Identity and Convolutional Blocks
- Final Dense + Softmax Layer

## 🚀 How to Run
1. Upload your dataset (`feraligned+ck`) zipped in Colab.
2. Run `facial_emotion_recognition.ipynb`.
3. Training and evaluation outputs will appear directly.

## 📊 Results
- Accuracy: ~XX% on test set
- Confusion matrix and classification report included

## 📄 License
MIT License
