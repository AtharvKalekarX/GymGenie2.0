# GymGenie
**AI-Powered Smart Fitness Platform**

GymGenie is a web-based fitness application that transforms a standard webcam into a personal AI trainer. It tracks exercises in real-time, gamifies workouts, and provides personalized AI coaching without requiring any external hardware or sensors.

## Key Features
* **Real-Time AI Tracking:** Uses computer vision to map 33 skeletal landmarks, calculate joint angles, and automatically count accurate repetitions for various exercises (e.g., Bicep Curls, Squats, Push-Ups).
* **Gamified Progression:** Earn XP for every rep, track daily streaks, level up, and compete on a global leaderboard. Includes weekly fitness challenges to keep you motivated.
* **Smart AI Coach ("Genie"):** A context-aware virtual coach powered by Google Gemini. It dynamically reads your biometric profile and recent workout history to provide highly personalized fitness and diet advice.
* **Cloud-Synced Dashboards:** Secure user authentication and real-time database storage ensure your workout history, custom profile pictures, and stats are safely backed up in the cloud.

## Tech Stack
* **Backend:** Python, Flask
* **AI & Computer Vision:** OpenCV, MediaPipe, NumPy, Google Gemini API
* **Database & Auth:** Firebase Firestore (NoSQL), Firebase Authentication
* **Frontend:** HTML5, CSS3, Bootstrap, Jinja2

## Prerequisites
Before you begin, ensure you have the following installed and set up:
* Python 3.8+
* A [Google Gemini API Key](https://aistudio.google.com/app/apikey)
* A Firebase Project with **Firestore Database** and **Email/Password Authentication** enabled.
