# sign-langugae-detection-using-machine-learning
This project trains a convolutional neural network to detect sign language letters/words from images (or webcam frames).

File tree
Sign-Language-Detection-Repo/
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── data/
│ └── download_data.py
├── src/
│ ├── __init__.py
│ ├── dataset.py
│ ├── models.py
│ ├── train.py
│ ├── infer.py
│ └── evaluate.py
├── notebooks/
│ └── QUICK_START.md

## Features
- Training pipeline using TensorFlow/Keras and `tf.data` for performance
- Data loader supporting folder-structured datasets (one folder per class)
- Model definition (CNN) and training script with checkpoints
- Inference script for single images and webcam real-time prediction
- Evaluation utilities (confusion matrix, classification report)

### Technologies and Tools
Python
TensorFlow
Keras
OpenCV
