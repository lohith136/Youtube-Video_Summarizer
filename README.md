# YouTube Video Summarizer

## 📌 Overview
This project extracts transcripts from YouTube videos, summarizes them using the Groq API, and saves the summarized text into a formatted text file with 10 words per line. The file is automatically downloaded to the user's device.

## 🚀 Features
- Extracts **video transcripts** from YouTube.
- Uses **Groq API** (Mixtral model) for summarization.
- Formats text to have **10 words per line**.
- Saves and **automatically downloads** the summary as a `.txt` file.

## 🛠️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/youtube-video-summarizer.git
cd youtube-video-summarizer
```

### 2️⃣ Install Required Libraries
Make sure you have Python installed, then install dependencies:
```bash
pip install requests youtube-transcript-api google-colab
```

### 3️⃣ Set Up Your API Key
- Get your **Groq API Key** from [Groq API](https://console.groq.com/)
- Replace `GROQ_API_KEY` in the script with your key.

## 🎯 Usage

### Run the Script
```bash
python summarizer.py
```

### Input the YouTube Video URL
- The script will ask for a YouTube URL.
- It will fetch and summarize the transcript.
- The summary will be saved as `summarized_text.txt` and downloaded automatically.

## 📁 Output
The summarized text is saved in a text file with **10 words per line** for readability. Example:
```
This is a sample summary file with ten words
per line making it easy to read and understand.
```

## 📝 To-Do
- Improve chunking method for longer videos.
- Implement GUI for better usability.
- Add support for multiple languages.

## 🤝 Contributing
Feel free to fork this repository and submit a pull request if you’d like to contribute!



