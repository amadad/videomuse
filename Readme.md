<div align="center">

# VideoMuse 🎵🎥

### AI-Powered Music Video Generator

<p>
<img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/amadad/videomuse" />
<img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/amadad/videomuse" />
<img alt="GitHub Repo Size" src="https://img.shields.io/github/repo-size/amadad/videomuse" />
<img alt="GitHub Stars" src="https://img.shields.io/github/stars/amadad/videomuse" />
<img alt="GitHub Forks" src="https://img.shields.io/github/forks/amadad/videomuse" />
<img alt="Github License" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
<img alt="Twitter" src="https://img.shields.io/twitter/follow/amadad?style=social" />
</p>

</div>

-----

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-features">Features</a> •
  <a href="#-how-it-works">How It Works</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-usage">Usage</a> •
  <a href="#-contributing">Contributing</a> •
  <a href="#-license">License</a>
</p>

-----

VideoMuse is an AI-powered application that generates custom music for your videos, creating unique and engaging music videos.

-----

## 📖 Overview

VideoMuse automates the process of creating music videos by analyzing the content of your video and generating a custom music track to accompany it. Using advanced AI models and audio processing techniques, VideoMuse produces high-quality music that complements your video's mood, style, and content.

## ✨ Features

* **Video Analysis**: Utilizes Google's Gemini AI to analyze video content and generate music prompts.
* **Custom Music Generation**: Creates unique music tracks based on video analysis using Suno AI.
* **Audio Overlay**: Seamlessly combines the original video with the generated music track.
* **User-Friendly Interface**: Easy-to-use Streamlit app for uploading videos and generating music videos.

## 🛠 How It Works

1. **Video Upload**: Users upload their video through the Streamlit interface.
2. **Video Analysis**: The video is analyzed using Google's Gemini AI to generate a music prompt.
3. **Music Generation**: Based on the prompt, custom music is created using Suno AI's API.
4. **Audio Processing**: The generated music is downloaded and overlaid onto the original video.
5. **Final Output**: A new music video is created, combining the original video with the custom music track.

## 🚀 Installation

1. Clone the repository:
   ```
   git clone https://github.com/amadad/videomuse.git
   ```
2. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Set up environment variables:
   - `GOOGLE_API_KEY`: Your Google API key for Gemini AI
   - `SUNO_API_KEY`: Your Suno AI API key

## 📊 Usage

1. Run the Streamlit app:
   ```
   streamlit run main.py
   ```
2. Upload your video file through the web interface.
3. Enter a prompt to guide the music generation (optional).
4. Click "Generate Music Video" to start the process.
5. Wait for the process to complete, and enjoy your new music video!

## 🤝 Contributing

Contributions to VideoMuse are welcome. Please ensure to follow the project's code standards and submit pull requests for review.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.