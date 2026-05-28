Gesture-to-Text and Speech-to-Text System

A real-time multimodal communication system that converts hand gestures into text and speech into text using Computer Vision and Speech Recognition techniques. This project is designed to improve accessibility and enable seamless human-computer interaction.

🚀 Features

✋ Real-time Gesture Recognition
🗣️ Speech-to-Text Conversion
📷 Live Webcam Integration
🎯 Hand Tracking using MediaPipe
🧠 Machine Learning-based Gesture Classification
🔊 Voice Recognition using SpeechRecognition API
🖥️ Simple and Interactive UI
⚡ Fast and Lightweight Processing


🛠️ Tech Stack

Languages

- Python

Libraries & Frameworks

- OpenCV
- MediaPipe
- TensorFlow / Keras
- NumPy
- SpeechRecognition
- PyAudio


📂 Project Structure

Gesture-to-Text-and-Speech-to-Text/
│
├── gesture_recognition/
│   ├── dataset/
│   ├── model/
│   ├── train_model.py
│   ├── predict_gesture.py
│
├── speech_to_text/
│   ├── speech_recognition.py
│
├── app/
│   ├── main.py
│
├── requirements.txt
├── README.md
└── LICENSE



📸 How It Works

- Gesture-to-Text

1. Webcam captures live hand gestures.
2. MediaPipe detects hand landmarks.
3. Trained ML model classifies gestures. 
4. Recognized gesture is converted into text.

NOTE: Please retrieve dataset for Alphabets Gestures from Kaggle. In this repository uploaded trained alphabets from m to z.


- Speech-to-Text

1. Microphone captures voice input.
2. SpeechRecognition processes audio.
3. Spoken words are converted into text output.


🧠 Machine Learning Workflow

Data Collection → Preprocessing → Feature Extraction →
Model Training → Gesture Prediction → Text Output



📋 Requirements

Example dependencies:

opencv-python
mediapipe
tensorflow
numpy
SpeechRecognition
pyaudio


Install manually if needed:

pip install opencv-python mediapipe tensorflow numpy SpeechRecognition pyaudio


🎯 Applications

* Assistive Technology for Deaf and Mute Communication
* Smart Human-Computer Interaction
* Accessibility Tools
* Real-time Captioning Systems
* Educational Projects

🔮 Future Enhancements

* Support for full sign language sentences
* Multilingual speech recognition
* Text-to-Speech integration
* Mobile application deployment
* Deep learning optimization for higher accuracy


🐞 Known Issues

* Background noise may affect speech recognition accuracy.
* Poor lighting can reduce gesture detection performance.
* PyAudio installation may require additional system dependencies.


⭐ Support

If you like this project, please give it a ⭐ on GitHub!
