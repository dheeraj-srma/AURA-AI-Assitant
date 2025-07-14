🌟 AURA – AI Assistant with Voice, Image, and Chat (CustomTkinter GUI)
AURA is a modern desktop AI assistant built with Python, CustomTkinter, and several AI & API integrations.
It supports text and voice chat, dynamic image generation & editing, real-time weather updates, animated side menus, and theming — all in a clean, modern GUI.


✨ Features
Modern GUI built with CustomTkinter

Voice and text chat (speech recognition + text-to-speech)

AI image generation and editing using Pollinations AI

Live weather display with OpenWeather API

Light and dark theme with saved preference

Smooth animated side menu

Chat history and option to save recent reply as PDF

Custom fonts and icons for a unique look

📦 Installation
Python version 3.9 or higher is recommended.

Clone the repository

git clone https://github.com/yourusername/aura-assistant.git
cd aura-assistant

Install required libraries

pip install -r requirements.txt

🔑 Configuration
Create a .env file in the project folder with your OpenWeather API key:

OPEN_WEATHER_API_KEY=your_openweather_api_key

Add icon images to these folders:

icons/light/
icons/dark/

🚀 Running the app
Inside your project folder, run:

python main.py

This will launch the GUI window showing:

Clock and weather at the top

Scrollable chat area

Bottom bar with mic, power, and image buttons

Smooth light/dark theme toggle

Animated tools side menu

🛠 Project structure
aura-assistant/
    backend.py → Handles AI, speech, and utility logic
    test.py → Main GUI app

fonts/ → Custom fonts

icons/ → Icon images (with light/ and dark/ folders)

settings.json → Stores theme preference

.env → API keys (not to be shared)

🧩 Built with
Python and Tkinter for GUI

CustomTkinter for themed, modern widgets

Pillow for image processing

Requests for API calls

Pollinations AI API for generating and editing images

OpenWeather API for live weather

Speech libraries for voice recognition and text-to-speech

✏️ Usage tips
Click the mic button to turn voice listening on or off

Click the image button to enter or exit AI image generation mode

Edit AI images by providing a new prompt after generating

Change city by clicking the location pin near the weather info

Use the side tools menu (☰) to:

Save recent AI response as PDF

View recent chat history

Switch theme between light and dark

Exit the application

📜 License
This project is open-source under the MIT License.

🙏 Thanks & credits
->CustomTkinter project
->Pollinations AI
->OpenWeather API
->GROQ API
->Icons 8

Open-source font authors

⭐ Contributions
Feedback, ideas, and pull requests are welcome!
You can open an issue or submit a PR anytime.
