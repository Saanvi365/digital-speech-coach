# Digital Speech Coach

An NLP tool that analyzes pacing, clarity, and confidence in a speech recording and gives real-time coaching feedback. Won 1st place at a local AI hackathon (Warrior Hacks).

## What it does

- Transcribes uploaded speech audio (Whisper / SpeechRecognition, any common audio format)
- Measures words per minute, volume (dBFS), filler-word usage, pitch variety, and enunciation rate
- Computes a confidence score and generates a full speech performance report with charts
- Gives personalized coaching tips and targeted practice exercises based on your metrics
- Includes a confidence journal to track reflections and progress over time
- Ships with a Gradio web UI for upload-and-analyze in the browser

## Tech stack

Python, OpenAI Whisper, SpeechRecognition, librosa, pydub, Gradio, NLTK, textstat, Matplotlib

## Running it

Open `speech_coach.ipynb` in Google Colab, run the cells in order, and upload a speech recording when prompted.
