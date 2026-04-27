# Arabic Speech-to-Text System (ASR) & Text-to-Speech (TTS)

This project presents a complete pipeline for building an **Arabic Automatic Speech Recognition (ASR)** and **Text-to-Speech (TTS)** system from scratch using Deep Learning and Natural Language Processing techniques.

The system was developed as part of an academic AI project to demonstrate how speech signals can be processed, converted into features, and used to train neural networks to recognize Arabic speech.

---

## 🚀 Project Overview

Speech recognition in Arabic is a challenging task due to dialectal variations and limited open datasets.  
This project demonstrates:

- Audio preprocessing and feature extraction (MFCC)
- Building Deep Learning models for speech recognition
- Training pipeline for Arabic speech data
- Text preprocessing and cleaning
- End-to-end ASR training notebook
- TTS experimental notebook

---

## 🧠 System Architecture

1. Audio input (`.wav`)
2. Feature extraction using MFCC (Librosa)
3. Deep Learning model (LSTM layers)
4. Text output prediction (`.lab` transcription)

---

## 📁 Project Structure

<pre> ## 📁 Project Structure ``` arabic-speech-to-text/ │ ├─ notebooks/ │ ├─ asr_training.ipynb │ └─ tts_model.ipynb │ ├─ src/ │ ├─ preprocessing.py │ ├─ model.py │ └─ utils.py │ ├─ dataset_sample/ │ └─ README.md │ ├─ requirements.txt └─ README.md ``` </pre>

---

## 📊 Dataset

The model was trained on an Arabic speech dataset consisting of audio files (`.wav`) and their corresponding transcriptions (`.lab`).

Due to dataset licensing, the dataset is not included in this repository.

You can reproduce the experiment using public Arabic datasets such as:

- Mozilla Common Voice (Arabic)
- OpenSLR Arabic Speech Corpus

---

## 🛠️ Technologies Used

- Python
- Librosa
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn

---

## ▶️ How to Run

1. Install requirements:

<pre> ``` pip install -r requirements.txt ``` </pre>


2. Open the notebooks:
   - `asr_training.ipynb`
   - `tts_model.ipynb`

3. Replace the dataset path with your Arabic speech dataset.

---

## 🎯 Project Goal

To demonstrate how Arabic speech can be processed and recognized using Deep Learning without relying on pre-trained speech models.

---

## 👤 Author

**Abdullah Ammar**  
AI & NLP Enthusiast
