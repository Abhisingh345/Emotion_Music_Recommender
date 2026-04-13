# Emotion_Music_Recommender
🚀 FACE EMOTION BASED MUSIC RECOMMENDER 🎭🎵

📌 Project Overview

This project detects a user's facial emotion in real-time using a webcam and recommends a suitable YouTube song based on the detected emotion. It integrates: 🎭 Face Emotion Detection using Deep Learning 📷 Real-time Webcam Capture (OpenCV)
🎵 YouTube Data API v3 Integration
🌐 Automatic YouTube song playback in browser
🔐 Secure API key management using .env

🧠 How It Works

Webcam captures live video.    
DeepFace analyzes facial expression.    
Dominant emotion is detected (Happy, Sad, Angry, Fear, Neutral, etc.).    
YouTube Data API searches songs based on detected emotion.    
Top result automatically opens in browser.
🛠️ Tech Stack

Python 3.13    
OpenCV    
DeepFace    
TensorFlow    
YouTube Data API v3    
Requests    
python-dotenv    
Git & GitHub
📂 Project Structure face-emotion-music-recommender/ │ ├── emotion_music.py ├── requirements.txt ├── .gitignore ├── README.md └── .env (not uploaded)

⚙️ Installation 1️⃣ Clone Repository git clone https://github.com/YOUR_USERNAME/face-emotion-music-recommender.git cd face-emotion-music-recommender 2️⃣ Install Dependencies pip install -r requirements.txt 3️⃣ Add Your YouTube API Key
Create a file named:
.env
Add:
YOUTUBE_API_KEY=your_api_key_here 4️⃣ Run Project python emotion_music.py
Press q to exit. Press m to play music in browser.

🎯 Features

✅ Real-time emotion detection ✅ Dynamic song recommendation ✅ Automatic YouTube playback ✅ Secure API key handling ✅ Clean GitHub-ready structure

📸 Sample Output Detected Emotion: sad Recommended Song: Tujhe Kitna Chahne Lage | Arijit Singh Opening in browser...

🔐 Security Note

API key is stored in .env file and excluded using .gitignore.

📚 Research & Concepts Used

Convolutional Neural Networks (CNN) Emotion Classification Models REST API Integration Environment Variables Management Real-Time Computer Vision

👨‍💻 Author

Harshit Gupta B.Tech Final Year Aspiring Software Development Engineer (SDE)

🌟 Future Improvements

Deploy as Web App (Flask / Streamlit) Add Spotify API integration Add GUI interface Store user emotion history Add mood-based playlist generation
