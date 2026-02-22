# 🍅 Pomodoro Timer
![GitHub License](https://img.shields.io/github/license/ix3twastaken/pomodoro-timer)  ![GitHub Repo stars](https://img.shields.io/github/stars/ix3twastaken/pomodoro-timer)

# 📝Description

A minimal **Pomodoro timer for Windows** built with Python.  
The application allows users to configure work and break intervals and automatically runs them in a loop with Windows toast notifications.

![pomodoro-timer-preview](https://gist.githubusercontent.com/ix3twastaken/999c600639ab33b26995c916760d842c/raw/0c5505ca38b20692aa4beaba4746995642016e62/pomodoro-timer-preview.png)

This project was created as:

- ✅ A personal productivity tool
- 📚 A learning project

## ✨ Features

- ⏱ Custom work duration
- ☕ Custom break duration
- 🔁 Automatic work → break cycle
- 🔔 Windows toast notifications
- 🛑 Stop button to interrupt the cycle

## 🧠 About the Pomodoro Technique

The Pomodoro technique is a time-management method based on focused work intervals followed by short breaks.

Classic format:

- 25 minutes of work
- 5 minutes of break
- Repeat

This app allows fully customizable intervals.

## 🚀 Installation

### 🔹 Option 1 — Download Prebuilt `.exe` (Windows)

1. Go to the **Releases** section.
2. Download the latest `.exe`.    
3. Launch the application.

### ⚠️ Security Notice

The `.exe` file is **not digitally signed**.
When launching it, Windows may show a **SmartScreen warning**.

If you trust this repository, you can:

1. Click **More info**
2. Select **Run anyway**

For maximum security, you can build the executable yourself from source (see below).

### 🔹 Option 2 — Run from Source

#### Requirements

- Python 3.9+
- dearpygui
- notify-py
- pyinstaller
#### Clone the repository

```bash
git clone https://github.com/ix3twastaken/pomodoro-mini-app.git  
cd pomodoro-timer
```
#### Install dependencies

```bash
pip install -r requirements.txt`
```
#### Build the executable

```bash
pyinstaller --name "Pomodoro timer" --onefile --windowed --add-data "src/assets;assets" --icon "src/assets/icon.ico" src/main.py
```

The executable will be generated inside the `dist/` folder.

## 📄 Credits
<a href="https://www.flaticon.com/free-icons/tomato" title="tomato icons">Tomato icons created by Pixel perfect - Flaticon</a>
