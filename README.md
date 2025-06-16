# 🗣️ Speech to Text Conversion Using Python

This project implements a **real-time speech-to-text transcription system** using Python. It allows users to convert speech from a microphone into text and automatically saves the transcript into a **PDF file**. Designed for accessibility and productivity, this tool is lightweight, user-friendly, and easy to use with simple key controls.

## 📌 Objective

To develop a speech-to-text system that:
- Transcribes spoken input in real-time
- Provides PDF output for saved transcripts
- Offers real-time feedback via console
- Uses simple keyboard controls (`s` to start, `e` to end)

## 🚀 Features

- Real-time transcription from microphone
- Outputs neatly formatted PDF (`output.pdf`)
- Supports keyboard interrupts to start/stop
- Adjusts for ambient noise
- Handles errors and missing audio devices gracefully
- Simple and effective UI via terminal

## 🧰 Tech Stack

- **Language:** Python 3.7+
- **Libraries:**
  - `speech_recognition`
  - `keyboard`
  - `fpdf`
  - `pyaudio`
- **Environment:** Visual Studio Code, Jupyter Notebook, Google Colab (optional)

## 🖥️ Installation

Make sure Python 3.7+ is installed.

```bash
pip install SpeechRecognition
pip install keyboard
pip install fpdf
pip install pipwin
pipwin install pyaudio
