# voice-to-text-translation
Application that translates speech into text and audio in different languages.

# Voice Translation and Speech Synthesis

This project is a Python-based voice translation and speech synthesis application that recognizes speech in multiple languages, translates it to a user-specified target language, and then generates an audio file of the translated text. The project uses the following libraries:

- `speech_recognition`: For capturing and recognizing speech from the microphone.
- `googletrans`: For translating recognized text to the desired language.
- `gTTS`: For converting the translated text into speech.

## Features

- Speech input is captured from the microphone.
- The recognized text is translated into a target language (e.g., Hindi, Telugu, Tamil, etc.).
- The translated text is converted into audio and saved as an MP3 file.
- Supports multiple languages including Hindi, Telugu, Tamil, Kannada, Malayalam, and Bengali.

## Installation

To set up and run the project, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/voice-translation.git
cd voice-translation
