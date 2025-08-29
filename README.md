 # Cough Severity Analysis using Machine Learning 

This project presents an end-to-end machine learning pipeline for analyzing cough sounds to classify them as 'healthy' or 'unhealthy'. The model's probabilistic output serves as a severity score, demonstrating a powerful application of audio classification for preliminary digital health screening.

The entire workflow, from data acquisition and feature extraction to model training and live inference, is implemented on Google Colab.

---

## Key Features

* **End-to-End Pipeline:** A complete workflow from raw audio to actionable prediction.
* **Advanced Audio Processing:** Utilizes the **Librosa** library to extract **Mel-Frequency Cepstral Coefficients (MFCCs)**, capturing the unique timbral and spectral characteristics of each cough.
* **Machine Learning Model:** Implements a **Random Forest Classifier** from **Scikit-learn** for robust and interpretable classification.
* **Live Inference:** Includes a function to process and predict the severity of a new, user-uploaded cough recording in real-time.

---

## Project Workflow

The project follows a standard machine learning pipeline:

`Audio Input` → `Preprocessing (Padding/Truncating)` → `Feature Extraction (MFCC)` → `Model Training (Random Forest)` → `Evaluation` → `Severity Prediction`



---

## Dataset

This project is built upon the **Coughvid Dataset**, a large, crowdsourced collection of cough recordings hosted on Kaggle. Due to its significant size (~9 GB), the dataset is not included in this repository.


