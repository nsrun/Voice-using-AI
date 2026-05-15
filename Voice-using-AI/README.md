# Proton Voice Assistant 🤖

Proton is an advanced AI-powered desktop voice assistant built with Python. It combines a sleek, modern Tkinter GUI with powerful automation capabilities, allowing you to control your Windows PC using voice or text.

## ✨ Key Features

- 🖥️ **Modern Desktop GUI:** Dark-themed interface with real-time logs and hybrid text/voice input.
- 🎤 **Voice Recognition:** Powered by Google Speech Recognition for high accuracy.
- 🔊 **Text-to-Speech:** Natural voice feedback using `pyttsx3`.
- ⚙️ **System Automation:** Control volume, take screenshots, and manage windows (minimize/maximize/close).
- 📂 **File Navigation:** Browse and open files/folders directly via voice.
- 🌐 **Web Intelligence:** Integrated search with Google, Wikipedia, YouTube, Maps, and News.
- ⌨️ **Keyboard Shortcuts:** Voice-activated copy, paste, undo, redo, and save commands.
- 🔐 **Secure Login:** Authentication system to protect your personal assistant.

## 📚 Libraries Explained

| Library | Purpose |
| :--- | :--- |
| **`pyttsx3`** | Converts text to audible speech (Text-to-Speech). Works offline and supports multiple voices. |
| **`SpeechRecognition`** | Translates your spoken voice into text using Google's Speech API. |
| **`pywhatkit`** | Used for advanced YouTube automation, allowing the assistant to play videos directly. |
| **`pyautogui`** | Enables the assistant to control the mouse, take screenshots, and manage windows. |
| **`pynput`** | Used to simulate keyboard presses for shortcuts like Copy, Paste, and Undo. |
| **`wikipedia`** | Fetches quick summaries and information directly from Wikipedia. |
| **`Tkinter`** | The standard Python library used to create the graphical user interface (GUI). |
| **`PyAudio`** | A cross-platform library that allows Python to access your computer's microphone. |

## 🛠️ Prerequisites

- **Python:** 3.8 or higher
- **Microphone:** Required for voice interaction
- **Internet:** Required for speech recognition and web-based queries

## 🚀 Installation

1. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *Note: If you face issues installing `PyAudio`, try `pip install pipwin` followed by `pipwin install pyaudio`.*

## 🔐 Authentication

Proton now features a secure login screen to prevent unauthorized access. Use the following default credentials:

- **Username:** `admin`
- **Password:** `proton123`

> [!TIP]
> You can change these credentials directly in the `LoginGUI` class within `Proton.py`.

## 🎮 Usage

Launch the assistant by running:
```bash
python Proton.py
```

### How to Interact
- **Voice:** Start every command with the wake word **"Proton"** (e.g., *"Proton, search for Python tutorials"*).
- **Text:** Type directly into the GUI input field and press Enter (no wake word needed).

## 🗣️ Available Commands

| Category | Commands Examples |
| :--- | :--- |
| **System Apps** | "Open Notepad", "Open Chrome", "Open Calculator", "Open Paint" |
| **YouTube** | "Open YouTube", "Play [song] on YouTube" |
| **Web Search** | "Search for [topic]", "Wikipedia [topic]" |
| **Navigation** | "Locate [place]", "Open Map", "Open News", "Weather in [city]" |
| **System Control** | "Volume up/down", "Mute", "Take a screenshot" |
| **Window Mgmt** | "Minimize window", "Maximize window", "Close tab/window" |
| **Keyboard** | "Copy", "Paste", "Select all", "Undo", "Redo", "Save file" |
| **Files** | "List files", "Open [number]", "Back" |
| **General** | "What time is it?", "What is the date?", "Hi/Hello", "Goodbye" |

## 📄 License

This project is licensed under the MIT License.
