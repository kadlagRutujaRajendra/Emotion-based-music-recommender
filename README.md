# 🎵 Emotion-Based Music Recommender System

An intelligent Python-based music recommendation system that detects user emotions and recommends songs accordingly. It enhances the user experience by playing music that aligns with the user's current emotional state using facial expressions or text input.

## 📌 Features

- Real-time emotion detection using webcam (via OpenCV)
- Emotion classification using deep learning (TensorFlow/Keras)
- Recommends songs based on detected emotion
- Local music playback or Spotify API integration
- Simple and interactive user interface

## 💻 Tech Stack

- **Language**: Python
- **Libraries**:
  - `OpenCV` – for image capture and processing
  - `TensorFlow` / `Keras` – for emotion detection model
  - `Tkinter` or `Flask` – for GUI or web interface
  - `Pygame` or `playsound` – for playing music
  - `Spotipy` – for integrating Spotify (optional)

## 😃 Detected Emotions

- Happy 😊  
- Sad 😢  
- Angry 😠  
- Neutral 😐  
- Surprise 😮  
- Fear 😱  

Each emotion is mapped to a playlist or a list of songs that fit the mood.

## 📂 Project Structure

emotion-music-recommender/
│
├── model/
│ └── emotion_model.h5 # Trained deep learning model
│
├── songs/
│ ├── happy/ # Folder with happy songs
│ ├── sad/ # Folder with sad songs
│ └── ...
│
├── static/ or templates/ # (If using Flask)
├── main.py # Main Python script
├── requirements.txt # Required Python libraries
└── README.md # Project documentation

### Prerequisites

- Python 3.x
- Webcam (for real-time emotion detection)

### Installation
git clone https://github.com/kadlagRutujaRajendra/emotion-music-recommender.git
cd emotion-music-recommender
pip install -r requirements.txt
python main.py

🧠 How It Works
Captures real-time image via webcam.
Detects face and processes it using pre-trained CNN model.
Classifies the emotion from the face.
Maps the emotion to a playlist or song folder.
Plays a song based on the detected emotion.


🙋‍♀️ Author
Developed by RUTUJA KADLAG
LinkedIn: https://www.linkedin.com/in/rutuja-kadlag-357544258
