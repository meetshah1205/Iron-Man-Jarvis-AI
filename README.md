<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
    <div id="readme-container"></div>


        
# Voice-Controlled Assistant (Jarvis)

This Python script creates a voice-controlled assistant using various libraries to perform tasks like fetching information from Wikipedia, opening websites, playing music, telling the time, and sending emails.

## Features

- **Wikipedia Search:** The assistant can search and provide information from Wikipedia.

- **Web Browsing:** Open YouTube, Google, and Stack Overflow directly using voice commands.

- **Music Player:** Play music from a specified directory.

- **Time Information:** Get the current time with a voice command.

- **Code Editor:** Open your preferred code editor with a voice command.

- **Email Sender:** Send emails using a voice command (configured for Gmail).

## Requirements

Make sure to install the required Python libraries:

\`\`\`bash
pip install pyttsx3 speechRecognition wikipedia
\`\`\`

## Usage

1. Run the script.

\`\`\`bash
python voice_assistant.py
\`\`\`

2. The assistant will greet you, and you can give voice commands based on the implemented features.

## Configuration

- **Music Directory:** Set the music directory in the script.

- **Code Editor Path:** Set the path to your code editor in the script.

- **Email Configuration:** Provide your Gmail credentials for sending emails.

## Dependencies

- [pyttsx3](https://pypi.org/project/pyttsx3/): Text-to-speech conversion library.

- [speech_recognition](https://pypi.org/project/SpeechRecognition/): Speech recognition library.

- [wikipedia](https://pypi.org/project/wikipedia/): Python wrapper for Wikipedia API.

## Note

- Replace the placeholder values in the script with your specific configurations.

- The email sending functionality is configured for Gmail; adjust it as needed.

Feel free to explore and enhance the assistant based on your requirements!
`;

</body>
</html>
