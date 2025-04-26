# YouTube Video Summarizer

A Streamlit web application that generates summaries of YouTube videos using AI. The app can:
- Extract transcripts from YouTube videos
- Generate AI-powered summaries
- Support multiple languages
- Provide interactive chat about video content

## Features
- 🎥 YouTube video integration
- 📝 Automatic transcript extraction
- 🤖 AI-powered summarization
- 💬 Interactive chat about video content
- 🌐 Multi-language support
- 🎨 Modern, dark-themed UI

## Setup
1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file with your Groq API key:
   ```
   GROQ_API_KEY=your_api_key_here
   ```
4. Run the app:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Enter a YouTube video URL
2. Select your preferred language
3. Click "Get Transcript" to view the video transcript
4. Use "Generate Summary" to get an AI-powered summary
5. Ask questions about the video content in the chat tab

## Requirements
- Python 3.9+
- Streamlit
- Groq API key
- Other dependencies listed in requirements.txt

## Note
Make sure to keep your `.env` file private and never commit it to version control. 