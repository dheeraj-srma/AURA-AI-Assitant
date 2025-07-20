AI Assistant GUI

A modern Python AI assistant GUI built with CustomTkinter.
Features a beautiful top bar showing:
🕓 Clock & date
🌤️ Dynamic weather details (temperature, humidity, AQI, precipitation, condition, location)
📊 Live system info (CPU, RAM, Disk with sparkline graphs, uptime, battery, IP)
🤖 AI status with animated dots: “Listening...”, “Thinking...”, “Generating...” etc.

Screenshot: (add your screenshot path here)

---

✨ Features:

✅ Beautiful top bar layout (left: app name & AI status; middle: system stats; right: weather)
✅ Animated AI status label
✅ Dynamic sparkline graphs for real-time CPU, RAM, and Disk usage
✅ Weather section with large temperature, icons, and matrix of details
✅ Responsive design: resizes smoothly on window resize
✅ Custom fonts & icon support
✅ Modular, clean code (TopBar as a custom CTkFrame)

---

📦 Installation:

Clone the repository:
git clone [https://github.com/yourusername/aura-assistant.git](https://github.com/dheeraj-srma/AURA-AI-Assistant.git)
cd AURA-AI-Assistant

Install dependencies:
pip install -r requirements.txt

Required packages include:

* customtkinter
* psutil
* matplotlib
* (Optional) pynvml if you plan to add GPU usage
* pillow (if using image icons)

---

🛠 Usage:

Make sure your fonts and icons are in the correct folders:

/fonts
├─ DAGGERSQUARE.ttf
├─ Bord Demo.ttf
└─ ... others

/icons
├─ weather.png
├─ location.png
└─ ...

Run the main file:
python Main.py

The top bar will appear showing live system stats, current weather, and AI status.

---

📌 Structure:

Main.py            (Main application file)
top_bar.py (Custom TopBar class with weather & system info)
backend.py         file with all backend logic
/fonts             (Custom fonts)
/icons             (Icons for weather, location, etc.)
README.md
requirements.txt

---

✏️ Customization:

* Change fonts by editing fonts dictionary and loading with CTkFont
* Replace emoji placeholders with your icon images (use CTkImage)
* Adjust sparkline colors and background in create\_sparkline
* Modify AI status text & animation speed in animate\_status

---

🚀 Example AI status usage:
topbar.set\_status("Listening")
topbar.set\_status("Generating")
topbar.set\_status("Thinking")

---

📸 Screenshots:
<img width="1120" height="847" alt="image" src="https://github.com/user-attachments/assets/7e23254e-7edd-4ed0-80cd-e053debebff1" />
<img width="1121" height="853" alt="image" src="https://github.com/user-attachments/assets/7d6e51a3-b446-4fb5-8161-582e39ab1a2a" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/4ba8ca92-5b3a-40a1-ba10-dcdac2b83425" />
<img width="750" height="135" alt="image" src="https://github.com/user-attachments/assets/70f60f17-3f05-4d99-a1de-2936e74657f0" />

---

📝 License:
MIT License. Feel free to use, modify, and share!

---

❤️ Credits:
CustomTkinter
Matplotlib
psutil
Designed by Dheeraj Sharma
