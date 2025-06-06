## 🎭 Emotion-Based Music Recommender (**Live Emoji Edition**)
**AI-Powered Real-Time Emotion Detection with Music & Emoji Integration**

An intelligent webcam-based emotion recognition system using MediaPipe and a custom-trained neural network. This app detects your facial and hand gestures to recognize your current emotion, then recommends emotion-specific music from YouTube. Emojis are dynamically overlaid on your webcam feed for a fun, expressive UI.


## 🚀 Key Features

- ✅ Real-Time Emotion Detection – Uses webcam with MediaPipe Holistic for landmark extraction.

- 🧠 Deep Learning Powered – Trained neural network model recognizes multiple emotions.

- 🎵 Emotion-Based Music Recommendations – Suggests songs on YouTube based on your mood.

- 🎭 Live Emoji Overlay – Displays matching emojis directly on your video feed.

- 📷 Streamlit UI – Easy-to-use interface with integrated video stream and controls.

- 🔎 Search Personalization – Filter music by language and singer preference.

- 🧪 Data Collection & Training Scripts – Easily expand or retrain the emotion model.
  

## 🧱 Tech Stack
-  **Frontend**: Streamlit + OpenCV
- **Model**: Keras (TensorFlow backend)
- **Landmarks**: MediaPipe Holistic (Face + Hands)
- **Emoji Overlay**: OpenCV image blending
- **Video Streaming**: streamlit-webrtcJS


## ⚙️ Setup Instructions
** 1. Install Dependencies**

pip install opencv-python mediapipe numpy tensorflow keras streamlit streamlit-webrtc

**2. Collect Emotion Data**

python data_collection.py

**3.Train the Model**

python data_training.py

**4. Run Live Emoji Emotion Detection**

python inference.py

**5. Run Music Recommender App**

streamlit run music.py



## 📞 How It Works

1. User opens the Streamlit app and provides their preferred language and singer (optional).

2. Webcam is activated, and real-time video is processed using MediaPipe Holistic to extract facial and hand landmarks.

3. Landmark data is fed into a trained deep learning model, which predicts the user's current emotion.

4. The predicted emotion is displayed on the video feed along with a matching emoji overlay.

5. User clicks "Recommend me songs", and the app opens a YouTube search page using the emotion, language, and singer as search keywords.

6. User enjoys personalized music recommendations based on how they’re feeling, all powered by real-time AI emotion recognition.



## 🎯 Emotion Classes Supported
- happy 😊

- sad 😢

- angry 😡

- cry 😭

- neutral 😐

- surprise 😲

- rock 🤘 (custom)

 You can add more by collecting .npy data and retraining the model.



## 🧠 Future Roadmap
- 📄 Emotion timeline logging

- 📁 Exportable emotion reports (CSV/PDF)

- 📈 Dashboard for emotion trends

- 🔊 Audio tone detection (multi-modal emotion)

- 🎙️ Voice-controlled music search





## 🤝 Contributions
We welcome pull requests! For major changes, please open an issue to discuss what you'd like to improve or add.


## 📧 Contact
**Developer**: Vaibhav

**Email**: sahuvaibhav064@gmail.com

**LinkedIn**: https://www.linkedin.com/in/vaibhav-chaudhary-615712272/


## 📜 License
MIT License © 2025 Vaibhav
