# Jarvis – AI Voice Assistant

Jarvis is a Python-based AI voice assistant designed to interact with users through voice commands. It combines speech recognition, text-to-speech, web automation, music playback, news retrieval, and AI-generated responses.

## Features

- Voice command recognition using SpeechRecognition
- Text-to-speech responses using pyttsx3 and gTTS
- Website shortcuts for commonly used platforms
- Music playback using predefined YouTube links
- News retrieval using NewsAPI
- AI-powered conversational responses using the OpenAI API

## Technologies Used

- Python
- SpeechRecognition
- pyttsx3
- gTTS
- Pygame
- OpenAI API
- NewsAPI
- Requests

## Project Structure

```text
jarvis-ai-voice-assistant/
├── main.py
├── musicLibrary.py
├── requirements.txt
├── .gitignore
├── .env.example
└── README.md
```

## Setup and Installation

1. Install Python 3.11.
2. Clone or download this repository.
3. Open a terminal in the project directory.
4. Install the dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

5. Configure your OpenAI and NewsAPI keys using environment variables.
6. Run the assistant:

   ```bash
   python main.py
   ```

## Environment Variables

Configure these variables locally:

- `OPENAI_API_KEY`
- `NEWS_API_KEY`

Never commit API keys or your `.env` file to GitHub.

## Future Improvements

- Improve wake-word detection and voice interaction
- Add more useful voice commands
- Improve error handling and API reliability
- Add a cleaner configuration system

## Author

Vasudev Sharma
