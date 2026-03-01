🎵 GTZAN Music Genre Classification 

📖 Overview

This project classifies music genres using the GTZAN dataset.
We explore two approaches:

🌟 Random Forest on MFCC features (tabular data)

🤖 Convolutional Neural Network (CNN) on Mel-spectrogram images

The CNN uses MobileNetV2 with transfer learning and data augmentation to improve generalization.

📂 Dataset

GTZAN Music Genre Dataset

10 genres, 100 audio files per genre (30 seconds each)

Available here

🛠️ Requirements

Python 3.8+

TensorFlow 2.x

Librosa

NumPy, Pandas, Matplotlib

Scikit-learn

Install dependencies via pip:

pip install tensorflow librosa numpy pandas matplotlib scikit-learn
🚀 Usage

Prepare spectrogram images from audio files:

python generate_spectrograms.py

Train CNN model:

python train_cnn.py

Evaluate the model:

python evaluate_model.py

Outputs accuracy and classification metrics for new data.

💡 Notes

The repository contains only code and scripts.

Dataset files are not included due to size. Please download from the GTZAN website.

Results may vary depending on training setup and dataset preprocessing.
