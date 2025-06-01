# 🎵 Voice Emotion Detection using RAVDESS

A machine learning project that detects human emotions (Neutral, Calm, Happy, Sad, Angry) from voice recordings using the RAVDESS dataset. The project extracts meaningful audio features using `librosa`, applies data augmentation, and uses the powerful `XGBoost` classifier for emotion classification.

 

## 📌 Project Highlights

- 🎙️ Audio-based emotion classification
- 🎯 5 filtered emotions: **Neutral, Calm, Happy, Sad, Angry**
- 🔊 Feature extraction using **MFCC**, Chroma, Mel Spectrogram, Spectral Contrast, ZCR
- 🔁 Data augmentation (noise injection & speed variation)
- 🚀 Trained using **XGBoost** with hyperparameter tuning
- 📈 Achieved up to **90% accuracy**
- 💾 Model and label encoder are saved and reusable
- 🧪 Simple prediction interface for new audio samples

 
## 📂 Dataset

- **RAVDESS**: Ryerson Audio-Visual Database of Emotional Speech and Song  
- Format: `.wav` audio files  
- Used only **speech audio** files  
- [RAVDESS Info](https://zenodo.org/record/1188976)

 
## 🧠 Technologies Used

| Category           | Tools/Packages                        |
|--------------------|----------------------------------------|
| Language           | Python                                 |
| Audio Processing   | Librosa, NumPy                         |
| Machine Learning   | XGBoost, scikit-learn                  |
| Data Augmentation  | Custom augmentation (noise, speed)     |
| Evaluation         | Accuracy, Confusion Matrix, F1 Score   |
| Visualization      | Matplotlib                             |
| Model Saving       | Joblib                                 |

 
 
