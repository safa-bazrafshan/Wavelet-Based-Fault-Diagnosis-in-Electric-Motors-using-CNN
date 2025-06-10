# Wavelet-Based Fault Diagnosis in Electric Motors using CNN

This project presents a deep learning framework for diagnosing common faults in electric motors using continuous wavelet transform (CWT) scalograms and Convolutional Neural Networks (CNNs). The system is designed to classify motor conditions such as:

- Healthy
- Broken Rotor
- Bearing Fault
- Combined Fault
- Sensor Noise

## 📊 Methodology
1. Simulated time-domain signals representing various motor conditions.
2. Transformed signals into 2D wavelet scalograms using the Morlet wavelet.
3. Built and trained a CNN model on the scalograms.
4. Evaluated model performance and visualized decision rationale using Grad-CAM.

## 🛠️ Technologies Used
- Python 3
- NumPy, SciPy, PyWavelets
- Matplotlib, OpenCV
- TensorFlow / Keras

## 🧠 Model Results
- Test Accuracy: ~100% (on small test set)
- Grad-CAM heatmaps show relevant feature activation.

## 📁 Structure
- signals/ – Simulated motor signals
- scalograms/ – Generated wavelet scalogram images
- models/ – Saved trained CNN models
- notebooks/ – Main Colab scripts and training flow

## 👤 Author
Safa Bazrafshan  
Independent Researcher  
Email: safa.bazrafshan@gmail.com
