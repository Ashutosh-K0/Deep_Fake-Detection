# 🎭 Deepfake Detection: Unmasking Synthetic Realities

This project focuses on detecting deepfake videos using a deep learning pipeline that combines **InceptionV3** for spatial feature extraction and a **Gated Recurrent Unit (GRU)** for temporal sequence analysis.

### 🔍 Objective
To build a lightweight and efficient model that accurately detects fake videos by analyzing both frame-level artifacts and temporal inconsistencies.

### ⚙️ Model Architecture
- **InceptionV3 (CNN)**: Extracts spatial features from video frames  
- **GRU (RNN)**: Captures temporal coherence across frames  
- **Output**: Binary classification — Real or Fake

### 📈 Key Results
- ✅ ~89% Test Accuracy  
- ✅ High Fake-Class Precision  
- ✅ Modular, Scalable, and Deployable

### 🚀 How to Run
```bash
python train_model.py      # Train the model
python predict_video.py    # Run predictions on input video
