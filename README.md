# Python Voice Assistant

This is a simple Python voice assistant that can perform various tasks based on voice commands. It utilizes speech recognition and text-to-speech modules to understand and respond to user input.

## Prerequisites

Ensure you have the following Python libraries installed:

- pyttsx3
- speech_recognition
- wikipedia
- smtplib (for sending emails)

You can install these libraries using pip:
pip install pyttsx3
pip install speechRecognition
pip install wikipedia

------------------------------------------------------------------------------------------------------------
## Features

- **Wikipedia Search:** Ask the assistant to search for information on Wikipedia.
- **Open Websites:** Direct the assistant to open websites like YouTube, Google, and Stack Overflow.
- **Weather Forecast:** Get the current weather forecast for a specific location.
- **Music Playback:** Play music from a specified directory based on your mood.
- **Check Time:** Ask the assistant for the current time.
- **Open Code Editor:** Launch your preferred code editor.
- **Send Emails:** Send emails through your Gmail account (requires authentication).

## Usage

1. Upon running the script, the assistant will greet you and wait for your command.
2. Speak your command clearly into the microphone.
3. The assistant will process your command and execute the corresponding task.

## Customization

- **Music Directory:** Update the `music_dir` variable in the script with the path to your music directory.
- **Email Configuration:** Replace the sender's email address and password in the `sendEmail` function with your own Gmail credentials.

## Contributing

Contributions are welcome! If you have any ideas for improvement or new features
