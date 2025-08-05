# 🤖 Smart Voice Chatbot

**Smart Voice Chatbot** is an interactive Arabic-speaking assistant (Saudi dialect) built with AI, speech recognition, and voice synthesis.  
It features a modern UI, real-time voice interaction, light/dark themes, and supports both text and voice chat.

---

## ✨ Features
- 🎤 **Real-time voice chat** using [ElevenLabs](https://elevenlabs.io) for speech generation.
- 🧠 **AI-powered conversations** with [Cohere API](https://cohere.ai) for Arabic NLP.
- 🗣 **Speech-to-text** via RealtimeSTT.
- 💬 **Dynamic chat interface** with a typewriter effect.
- 🎨 **Light/Dark mode** with vibrant colors.
- 📱 **Responsive design** for all devices.

---

## 🛠️ Requirements
- [Anaconda](https://www.anaconda.com/) installed
- Python 3.10
- API Keys from:
  - [Cohere](https://dashboard.cohere.com/api-keys)
  - [ElevenLabs](https://elevenlabs.io)

---

## 📥 Installation & Setup

### **First Terminal (Main Setup)**
# 1. Open Anaconda Prompt
# 2. Install Git
conda install git

# 3. Create and activate environment
conda create -n CHAT_env python=3.10
conda activate CHAT_env

# 4. Clone the repository
git clone https://github.com/M40aha/MChatbot.git

# 5. Navigate to project folder
cd MChatbot

# 6. Install requirements
pip install -r requirements.txt

# 7. Install RealtimeSTT
pip install RealtimeSTT

# 8. Start the RealtimeSTT server
python RealtimeSTT_Server.py



Second Terminal (Run Chatbot Backend):
conda activate CHAT_env
cd MChatbot
python Chatbot.py


🚀 How to Use:
Open the app in your browser..
http://localhost:5000
Click the 🎤 microphone button to speak, or type in the input box.
Toggle 🌞/🌙 to switch between light and dark mode.



📂 Project Structure

📁 MChatbot
 ├── Chatbot.py            # Backend server
 ├── RealtimeSTT_Server.py # Real-time speech server
 ├── index.html            # Frontend UI
 ├── style.css             # Styling
 ├── script.js             # UI logic
 ├── realtime.js           # Speech processing
 ├── requirements.txt      # Dependencies
 └── README.md             # This file
📸 Screenshot


Developed by Eng. Maha Alamri.
