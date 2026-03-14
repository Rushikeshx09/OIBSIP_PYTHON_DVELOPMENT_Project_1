Python Voice Assistant (Basic + Advanced)

A Python-based Voice Assistant that can understand voice commands and perform tasks such as telling the time, searching the web, sending emails, checking weather updates, and controlling smart home devices.

This project demonstrates both Beginner and Advanced implementations of a Voice Assistant using Speech Recognition, NLP concepts, and API integrations.

📌 Project Overview

This repository contains two versions of a voice assistant:

🟢 Basic Voice Assistant

A simple assistant designed for beginners that can:

Respond to greetings like Hello

Tell the current time

Tell the current date

Perform web searches

Exit when the user says Exit

This version helps understand the fundamentals of speech recognition and text-to-speech systems.

🔵 Advanced Voice Assistant

The advanced version introduces a modular architecture and additional capabilities such as:

🌦️ Weather updates using APIs

📧 Sending emails

⏰ Setting reminders

🏠 Smart home device control

🧠 Keyword-based Natural Language Processing

🔐 Basic encryption for security

📝 Logging system for debugging

⚙️ Configuration using environment variables

This version demonstrates real-world assistant architecture and automation.

🚀 Features
Basic Assistant

Voice command recognition

Text-to-speech responses

Time and date information

Web search functionality

Greeting interaction

Advanced Assistant

Modular architecture

Weather API integration

Email automation

Smart home device control

Reminder system

NLP-based intent detection

Security module (encryption)

Logging and error handling

Configurable API keys

🛠️ Technologies Used

Python

SpeechRecognition

pyttsx3

requests

datetime

logging

Regular Expressions (re)

Environment Variables

Google Speech API

📂 Project Structure
Voice-Assistant/
│
├── basic_voice_assistant.py
├── advanced_voice_assistant.py
├── README.md
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/voice-assistant.git
2️⃣ Open Project Folder
cd voice-assistant
3️⃣ Install Dependencies
pip install SpeechRecognition
pip install pyttsx3
pip install requests
pip install googlesearch-python
pip install pyaudio
▶️ Usage
Run Basic Assistant
python basic_voice_assistant.py

Example commands:

"Hello"

"What is the time?"

"What is today's date?"

"Search Python programming"

Run Advanced Assistant
python advanced_voice_assistant.py

Example commands:

"What's the weather?"

"Send email to example@gmail.com"

"Turn on the living room light"

"Set reminder for meeting"

🔑 Environment Variables (Advanced)

Set API keys before running the advanced assistant:

WEATHER_API_KEY=your_weather_api_key
EMAIL_API_KEY=your_email_api_key
SMART_HOME_API_KEY=your_smart_home_api_key
ENCRYPTION_KEY=your_secret_key
🧠 Key Concepts Implemented
Speech Recognition

Captures voice input and converts it into text using the SpeechRecognition library.

Natural Language Processing

Keyword-based intent detection is used to understand the user's command.

API Integration

External APIs are used for weather information, email automation, and smart home control.

Security

Basic encryption mechanism implemented to protect sensitive data.

Error Handling

Handles microphone errors, network failures, and API issues gracefully.

⚠️ Challenges Faced

Handling background noise in voice recognition

Managing API errors and network timeouts

Designing a modular assistant architecture

Processing natural language commands effectively

🚀 Future Improvements

Integrate AI models (GPT / LLM) for better conversation

Add Graphical User Interface (GUI)

Add music playback support

Add multi-language support

Integrate home automation platforms

Improve Natural Language Understanding

🤝 Contribution

Contributions are welcome!
Feel free to fork the repository and submit pull requests.

📜 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Rushikesh Basaveshwar Swami

Python Developer | Learning AI, Automation, and Voice Interfaces
