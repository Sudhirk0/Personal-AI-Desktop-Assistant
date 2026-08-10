# Alexa-Personal-AI-Desktop-Assistant
**Alexa – Personal AI Desktop Assistant** is your smart companion for everyday tasks. It understands voice commands, manages your schedule, opens apps, fetches information, and automates desktop actions. Built for productivity and ease, Alexa brings intelligent assistance right to your desktop.

🎙️ Desktop Voice Assistant (Python)
A simple Python-based virtual voice assistant inspired by Alexa. It listens to voice commands via microphone, converts speech to text, executes desktop/web tasks, and responds using text-to-speech synthesis.

✨ Features
🎵 Play Songs on YouTube: Speak play [song name] to automatically search and play video content on YouTube.

⏰ Check Current Time: Ask for the time to hear the current local time in 12-hour format.

🔍 Wikipedia Searches: Ask who the heck is [person name] to fetch and read out a 1-sentence summary from Wikipedia.

😂 Tell Jokes: Request a joke to hear a random programming joke using pyjokes.

🤖 Interactive Responses: Includes fun hardcoded voice responses to casual conversational prompts.

🛠️ Prerequisites & Installation

1. Clone the Repository
Bash
git clone https://github.com/your-username/desktop-voice-assistant.git
cd desktop-voice-assistant
2. Install Required Python Packages
Ensure you have Python 3.7+ installed. Install all necessary dependencies using pip:

Bash
pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes PyAudio
Note for PyAudio:

If you encounter errors while installing PyAudio, run the following depending on your OS:

Windows: pip install pipwin then pipwin install pyaudio

Linux (Ubuntu/Debian): sudo apt-get install portaudio19-dev python3-pyaudio

macOS: brew install portaudio then pip install pyaudio

🚀 Usage
Run the main Python script to start listening for voice commands:

Bash
python main.py



📂 Project Structure
Plaintext
desktop-voice-assistant/
│
├── main.py             
├── README.md           
└── requirements.txt   
