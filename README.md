# AI-lecture-assistant
## Overview
This web application allows users to upload an audio file (`.mp3` or `.wav`), transcribe its content into text, summarize the transcribed text, and listen to the summarized version using text-to-speech.

## Features
- **Upload Audio**: Supports `.mp3` and `.wav` files.
- **Transcription**: Converts audio speech into text.
- **Summarization**: Generates a concise summary of the transcribed text.
- **Text-to-Speech (TTS)**: Reads the summarized text aloud with playback controls (Play, Pause, Resume, Stop).
- **User-Friendly UI**: Built with Tailwind CSS for a modern, responsive design.

## Technologies Used
- **Frontend**: HTML, JavaScript, Tailwind CSS
- **Backend**: Flask (Python)
- **APIs**: Gemini API (for summarization), Web Speech API (for text-to-speech)

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Flask (`pip install flask`)
- Required dependencies (`pip install -r requirements.txt`)

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/ai-audio-transcription.git
   cd ai-audio-transcription
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask server:
   ```bash
   python app.py
   ```
4. Open the application in your browser at:
   ```
   http://127.0.0.1:5000/
   ```

## Usage
1. Upload an audio file.
2. Wait for transcription to complete.
3. Click "Summarize" to generate a summary.
4. Use the playback controls to listen to the summary.
