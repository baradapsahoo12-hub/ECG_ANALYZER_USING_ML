# ECG_ANALYZER_USING_ML
Developed an ECG abnormality detection system using signal processing and a Random Forest model, deployed as a Streamlit app for real-time analysis.
# 🫀 CardioSense – ECG Abnormality Detection

A machine learning-based ECG analysis system that uses Digital Signal Processing (DSP) and a Random Forest model to detect cardiac abnormalities and estimate severity.

# 🚀 Quick Start:

### 📦 Step 1: Download
Download the CardioSense.zip file from the repository.

### 📂 Step 2: Extract
Extract the ZIP file.

You should see:
app.py
ecg_model.pkl
run_app.bat
test_data/

### ▶️ Step 3: Run the App
Double-click on run_app.bat

### 🧪 Step 4: Test the App
Enter ECG file path (without extension), for example:
test_data/normal/100
test_data/abnormal/118

## ✨ Features
- ECG signal preprocessing using bandpass filtering
- R-peak detection and heart rate analysis
- Feature extraction from ECG segments
- Random Forest-based classification
- Severity estimation of abnormal signals
- One-click execution using .bat file
- Interactive web app using Streamlit

- ## 📊 Model Performance
- Accuracy: 0.706
- Precision: 0.693
- Recall: 0.494
- F1 Score: 0.576

Confusion Matrix:
[[1148, 201],
 [465, 454]]
