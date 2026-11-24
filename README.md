https://ai-gym-coach-ktsfd6dni5ymcjas8mvjl4.streamlit.app/



# AI Gym Coach – Fitness Assistant

An AI-powered fitness assistant that uses real-time computer vision and pose estimation to track workout repetitions, analyze exercise movements, and provide personalized voice-based coaching feedback.

## Features

- **Real-Time Pose Estimation:** Tracks body movements at 25 FPS using MediaPipe and OpenCV.
- **Repetition Tracking:** Automatically counts exercise repetitions based on detected body movements.
- **Movement Analysis:** Analyzes exercise form and movement patterns across 4 different exercises.
- **AI-Powered Coaching:** Integrates Groq LLM to generate contextual fitness feedback.
- **Voice Feedback:** Uses gTTS to deliver interactive voice-based coaching.
- **Live Streaming:** Uses WebRTC for real-time video processing and interaction.

## Tech Stack

- **Programming Language:** Python
- **Computer Vision:** OpenCV
- **Pose Estimation:** MediaPipe
- **AI Integration:** Groq LLM
- **Frontend:** Streamlit
- **Real-Time Communication:** WebRTC
- **Text-to-Speech:** gTTS

## Performance

- Achieved **25 FPS** real-time pose estimation.
- Achieved **90% repetition-counting accuracy** across 15 test videos.
- Supports movement analysis across **4 exercises**.

## How It Works

1. Captures live video through the webcam using WebRTC.
2. Detects and tracks body landmarks using MediaPipe.
3. Processes movement patterns using OpenCV.
4. Tracks repetitions and analyzes exercise movements.
5. Uses Groq LLM to generate contextual coaching feedback.
6. Converts feedback into voice output using gTTS.
