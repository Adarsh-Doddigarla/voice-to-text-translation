# Voice-to-Text Translation Application

This project is a Python-based application that captures voice input, recognizes the spoken text, detects its language, translates it into a target language, and generates an audio file in the translated language.

## Features

- **Captures voice input** using the microphone.
- **Recognizes spoken text** using Google Speech Recognition.
- **Detects the language** of the recognized text.
- **Translates the recognized text** into a user-specified target language.
- **Converts the translated text** into an audio file using Google Text-to-Speech (gTTS).

## Prerequisites

Before running the application, ensure you have the following:

- **Python 3.7 or higher** installed on your system.
- The required Python libraries. You can install them via `pip` by following the steps below.

### Required Libraries

Install the required libraries using `pip`:

```bash
pip install -r requirements.txt
```

Ensure your microphone is connected and accessible for speech input.

## Installation

1. **Clone this repository**:

```bash
git clone https://github.com/your-username/voice-to-text-translation.git
cd voice-to-text-translation
```

2. **Install the required libraries**:

```bash
pip install -r requirements.txt
```

3. **Ensure your microphone is working** and accessible for speech input.

## Usage

1. **Run the application** by executing the following command:

```bash
python app.py
```

2. **Input the target language**: When prompted, enter the target language (e.g., Hindi, Telugu, Tamil, etc.).
   
3. **Speak into the microphone** when instructed. The application will:

   - Recognize your speech.
   - Detect the language of the recognized text.
   - Translate the text into the specified target language.
   - Save the translated audio as an MP3 file in the `outputs/` folder.
   
4. **Play the translated audio**: The translated audio will automatically play if your system supports the playback command.

## Supported Languages

The application currently supports translation to the following languages:

- **Hindi** (`hi`)
- **Telugu** (`te`)
- **Kannada** (`kn`)
- **Tamil** (`ta`)
- **Malayalam** (`ml`)
- **Bengali** (`bn`)

## File Structure

Here’s the structure of the project:

```
voice-to-text-translation/
│-- app.py              # Main application script
│-- requirements.txt    # Required libraries
│-- outputs/            # Directory where translated audio files are saved
```

## Requirements File

Create a `requirements.txt` file with the following content:

```
speech_recognition
googletrans==4.0.0-rc1
gtts
```

## Notes

- **Google Translate (googletrans)**: This library may experience occasional issues with translations. If translation fails, check your network connection or try again later.
- **Outputs directory**: The `outputs/` directory will be created if it does not already exist during script execution. Ensure that the folder is accessible.

---
