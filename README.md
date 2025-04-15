# PROJECT:   Speech to Text & Text to Speech Converter


This Python project offers a **user-friendly GUI-based application** that allows users to seamlessly convert **text to speech** and **speech to text**. Built with `tkinter`, and powered by `gTTS` (Google Text-to-Speech) and `SpeechRecognition`, this tool is ideal for anyone needing fast and easy voice-to-text or text-to-voice conversion.
  
![image](https://github.com/user-attachments/assets/bb778369-5c05-456f-b86d-b40ce3bf19eb)


## 🚀 Features

✅ **Text to Speech Conversion**  
Convert typed text into audio using selected language accents. Save and play the speech as an MP3 file.

✅ **Speech to Text Conversion**  
Record voice via microphone and transcribe it into text using Google's Speech Recognition API.

✅ **Multilingual Support**  
Supports various languages and accents for Text-to-Speech conversion.

✅ **Graphical User Interface**  
An intuitive interface built with `tkinter`, allowing non-technical users to use the app effortlessly.

## 🛠️ How It Works

1. **Text Input:** Enter text and choose your language code (e.g., `en` for English).
2. **Generate Speech:** Click "Convert Text to Speech" to generate and play audio.
3. **Record Speech:** Enter duration, click "Convert Speech to Text", and speak into your mic.
4. **View Output:** The transcribed text appears in a popup window.
5. **Languages List:** Click "List Languages" to view supported TTS language codes.

## 🧰 Tech Stack & Libraries

## gTTS (Google Text-to-Speech):**
Converts written text into spoken words, generating MP3 files.
Useful for applications needing voice output.

## SpeechRecognition:**
Enables your application to recognize speech and convert it to text.
Supports multiple speech engines and APIs.

## tkinter:**
The standard GUI toolkit for Python; perfect for building user interfaces.
Allows you to create windows, buttons, and other interactive elements.

## playsound:**
Simple library to play MP3 audio files.
Can be used for playing back audio generated by gTTS.

## pyaudio:**
Provides a way to capture audio from the microphone.
Essential for applications that need to process live audio input.

### Example Workflow:**
You could combine these libraries to create an application that:

Uses tkinter to build a user-friendly interface.

Captures audio input through pyaudio, converting it to text with SpeechRecognition.

Processes the text (e.g., translates or modifies it).

Converts the final text back to speech using gTTS.

Plays the resulting speech with playsound.

## 📦 Installation

Make sure Python 3 is installed.

Install dependencies using pip:

pip install gTTS SpeechRecognition pyaudio playsound


If you face issues with pyaudio, install it using:


•	For Windows:

pip install pipwin

pipwin install pyaudio

## 💻 Usage**
1.	Clone the repository or download the script.
2.	Run the Python script:
python speech_text_converter.py
3.	Use the GUI:
o	Type text and choose a language code for TTS.
o	Set recording time and speak for STT.
o	Use the buttons to convert and view results.

## 🌐 Supported Languages**

Use the “List Languages” button in the GUI to view the list of supported languages and their respective codes (e.g., en, hi, fr, etc.).

## 🙌 Acknowledgments**

•	gTTS
•	SpeechRecognition
•	Python Tkinter Documentation


## 👩‍💻 Author**

Gudepu Rakshitha Reddy

Email: rakshithareddy1985@gmail.com

