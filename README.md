# SPEECH-RECOGNITION-SYSTEM

*COMPANY*: CODTECH IT SOLUTUIONS

*NAME*: JAYAL SHAH

*INTERN ID*: CODF94

*DOMAIN*: Artificial Intelligence Markup Language

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH



---

# 🗣️ Speech Recognition System

This repository features a basic yet functional **Speech Recognition System** developed in Python. The tool converts spoken words from an audio file into written text using the powerful capabilities of the `speech_recognition` library and Google’s Speech Recognition API.

The project is designed as an entry-level implementation to demonstrate the fundamental principles of speech-to-text conversion. It can be used for educational purposes, small automation tasks, or as a foundation for more advanced voice-processing applications.

---

## 🎧 How It Works

This speech recognition system operates through a simple and intuitive process. Here's a step-by-step breakdown:

1. **Importing Libraries**:
   The script relies on Python’s popular `speech_recognition` library, which serves as a wrapper for several speech-to-text APIs, including Google’s free Web Speech API.

2. **Audio File Handling**:
   The system reads an audio file (`Recording-1.wav`) using the `AudioFile` class provided by the library. This is wrapped in a context manager to ensure proper resource handling.

3. **Speech Recognition Engine**:

   * A `Recognizer` object is initialized to handle audio analysis.
   * The `listen()` method captures the contents of the audio file and stores it in an `AudioData` object.
   * This audio content is then passed to the `recognize_google()` method, which sends the data to Google's API for transcription.

4. **Error Handling**:
   The script includes exception handling to manage scenarios where the speech recognition API might be unreachable or if transcription fails. A friendly message prompts the user to retry in such cases.

5. **Output**:
   Once the audio is successfully transcribed, the result is printed to the console as plain text.

---

## 🛠 Requirements

To run this script, you'll need to install:

```bash
pip install SpeechRecognition
```

You’ll also need a `.wav` audio file (`Recording-1.wav`) placed in the same directory as the script. Other formats like `.mp3` can be used with additional libraries like `pydub` for format conversion.

---

## ✅ Features

* Reads `.wav` audio files.
* Converts speech to text using Google’s free API.
* Minimal setup with straightforward code structure.
* Built-in error handling for robust execution.

---

## 📚 Use Cases

This tool can be used for:

* Automating voice transcriptions.
* Building voice-controlled applications.
* Preprocessing audio data for machine learning.
* Creating accessible content from spoken words.

---

## 🚀 Future Improvements

While this is a simple implementation, the system can be extended in various ways:

* Support for real-time microphone input.
* Integration with other APIs (e.g., IBM Watson, Azure Speech).
* Audio file upload via a GUI or web interface.
* Language customization and accent support.

---

## 📤 Output:

![Image](https://github.com/user-attachments/assets/a4e5eff6-e8a2-45f4-a7c6-5d5bb1dc33ef)



This project is perfect for anyone getting started with voice processing or looking to build basic speech interfaces. Feel free to clone the repo, customize the code, and expand on the foundation to suit your project needs.

---
