# Jarvis-Voice-Activated-Virtual-Assistant
Jarvis is an AI-powered voice-activated virtual assistant built in Python. It listens for the wake word “Jarvis” and performs a wide range of tasks such as web browsing, playing music, fetching news, and answering user queries using OpenAI's GPT-3.5-turbo model.

🚀 Key Features
Voice Recognition: Listens and responds to voice commands using the speech_recognition library.
Wake Word Detection: Activates when it hears the word "Jarvis".
Text-to-Speech: Uses both pyttsx3 (offline) and gTTS (online) to speak back to the user.
Web Browsing: Opens popular websites like Google, YouTube, Facebook, and LinkedIn.
Music Playback: Plays music via a custom musicLibrary module.
News Updates: Fetches the latest headlines using NewsAPI.
GPT Integration: Handles complex queries using OpenAI’s GPT-3.5-turbo model.

🧠 How It Works
Initialization: Greets the user with “Initializing Jarvis…”
Wake Word Detection: Continuously listens for the word “Jarvis”.
Command Handling: Executes actions like opening websites, playing music, fetching news, or answering questions via OpenAI.
Speech Output: Responds using synthesized speech via pyttsx3 or gTTS.

🛠 Libraries Used
speech_recognition
pyttsx3
gTTS
pygame
openai
webbrowser
requests
os
musicLibrary (custom module)

