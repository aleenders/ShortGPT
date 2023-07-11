
# 🎬🚀 ShortGPT
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![](https://dcbadge.vercel.app/api/server/uERx39ru3R?compact=true&style=flat)](https://discord.gg/uERx39ru3R)
[![GitHub star chart](https://img.shields.io/github/stars/rayventura/shortgpt?style=social)](https://star-history.com/#rayventura/shortgpt)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/rayventurahq.svg?style=social&label=Follow%20%40RayVentura)](https://twitter.com/RayVenturaHQ) 
<div align="center">
    <img src="https://github.com/RayVentura/ShortGPT/assets/121462835/d9f87cf2-021d-4b8d-bb86-b3a7af1d80d4" alt="ShortGPT-logo" style="border-radius: 20px;" width="22%"/>
</div>

<div align="center">
  <a href="https://discord.gg/HUpRgp2HG8">
    <img src="https://img.shields.io/badge/discord-join%20chat-blue.svg" alt="Join our Discord" height="34">
  </a>
</div>

⚡ Automating video and short content creation with AI ⚡

## 📝 Introduction to ShortGPT 

🚀 ShortGPT is an open-source AI framework for automating video and short content creation.

- 🎬 The `ContentShortEngine` is designed for creating shorts, handling tasks from script generation to final rendering, including adding YouTube metadata.

- 🎥 The `ContentVideoEngine` is ideal for longer videos, taking care of tasks like generating audio, automatically sourcing background video footage, timing captions, and preparing background assets.
  
- 🎞️ The `EditingFlow`, using Editing Markup Language and JSON, breaks down the editing process into manageable and customizable blocks, comprehensible to Large Language Models.

💡 ShortGPT offers customization options to suit your needs, from language selection to watermark addition.

🔧 As a framework, ShortGPT is adaptable and flexible, offering the potential for efficient, creative content creation.

## Showcase


## 🚀 ShortGPT Features

ShortGPT is a powerful tool for automating content creation. It simplifies video creation, footage sourcing, voiceover synthesis, and editing tasks.

- 🎞️ **Automated editing framework**: Streamlines the video creation process with an LLM oriented video editing language.

- 📃 **Scripts and Prompts**: Provides ready-to-use scripts and prompts for various LLM automated editing processes.

- 🗣️ **Voiceover Creation**: Supports multiple languages including English 🇺🇸, Spanish 🇪🇸, Arabic 🇦🇪, French 🇫🇷, Polish 🇵🇱, German 🇩🇪, Italian 🇮🇹, and Portuguese 🇵🇹.

- 🔗 **Caption Generation**: Automates the generation of video captions.

- 🌐🎥 **Asset Sourcing**: Sources images and video footage from the internet, connecting with the web and Pexels API as necessary.
- 🧠 **Database Management**: Ensures long-term persistency of automated editing variables with TinyDB.

# Instructions for running shortGPT

This guide provides step-by-step instructions for installing ImageMagick and FFmpeg on your system, which are both required to do automated editing. Once installed, you can proceed to run `shortgptUI.py` successfully.

## Prerequisites

Before you begin, ensure that you have the following prerequisites installed on your system:
- Python 3.x
- Pip (Python package installer)

## Installation Steps

Follow the instructions below to install ImageMagick, FFmpeg, and clone the shortGPT repository:

### Step 1: Install ImageMagick

1. For `Windows` download the installer from the official ImageMagick website and follow the installation instructions.
      
      [https://imagemagick.org/script/download.php](https://imagemagick.org/script/download.php)
      
     
2. For Ubuntu/Debian-based systems, use the command:
     ```
     sudo apt-get install imagemagick
     ```   
    For macOS using Homebrew, use the command:
     ```
     brew install imagemagick
     ```

2. Verify the installation by running the following command:
   ```
   convert --version
   ```

   You should see the ImageMagick version information if the installation was successful.

### Step 2: Install FFmpeg

1. For `Windows`Download the FFmpeg binaries from the official website and add the executable to your system's PATH. 
      
      [https://ffmpeg.org/download.html](https://ffmpeg.org/download.html)
      
2. For macOS using Homebrew, use the command:
     ```
     brew install ffmpeg
     ```   
    For Ubuntu/Debian-based systems, use the command:
     ```
     sudo apt-get install ffmpeg
     ```
2. Verify the installation by running the following command:
   ```
   ffmpeg -version
   ```

   You should see the FFmpeg version information if the installation was successful.

### Step 3: Clone the shortGPT Repository

1. Open a terminal or command prompt.
2. Execute the following command to clone the shortGPT repository:
   ```
   git clone https://github.com/rayventura/shortgpt.git
   ```

### Step 3: Install Python Dependencies

1. Open a terminal or command prompt.
2. Navigate to the directory where `shortgpt.py` is located (the cloned repo).
3. Execute the following command to install the required Python dependencies:
   ```
   pip install -r requirements.txt
   ```

   This command will install the necessary packages specified in the `requirements.txt` file.

## Running shortgptUI.py Web Interface

Once you have successfully installed ImageMagick, FFmpeg, and the Python dependencies, you can run `shortgpt.py` by following these steps:

1. Open a terminal or command prompt.
2. Navigate to the directory where `shortgptUI.py` is located (the cloned repo).
3. Execute the following command to run the script:
   ```
   python shortgptUI.py
   ```
4. After running the script, a Gradio interface should open at your local host on port 31415 (http://localhost:31415). 

## Putting API Keys
The ShortGPT UI needs you to input at least OpenAI and ElevenLabs api keys for running short automations. For video automations, you will also need to add a Pexels API.

Follow these steps to add your OpenAI and ElevenLabs API keys:

1. Open [http://localhost:31415](http://localhost:31415) from a web browser. 
2. Click on the `config` tab located at the left side bar of the user interface.
3. Add your `OPENAI API KEY` and `ELEVENLABS API KEY` in the corresponding input fields.
4. Click `Save` to save your API keys.

That's it! You have successfully set up your API keys and can now utilize the functionality of ShortGPT in the Gradio interface.

## 💁 Contributing

As an open-source project in a rapidly developing field, we are extremely open to contributions, whether it be in the form of a new feature, improved infrastructure, or better documentation.


## 🔗 Get in touch on Twitter 🐦

Keep up with the latest happenings, announcements, and insights about Short-GPT by checking out our Twitter accounts. Spark a conversation with our developer and the AI's own account for fascinating dialogues, latest news about the project, and more.

- **Developer**: Stay updated [@RayVentura](https://twitter.com/RayVentura). Deep-dive into behind-the-scenes, project news, and related topics from the brain behind ShortGPT.

We're eager to interact with you and listen to your feedback, concepts, and experiences with Auto-GPT. Come on board on Twitter and let's navigate the future of AI as a team! 💡🤖

<p align="center">
  <a href="https://star-history.com/#ReyVentura/ShortGPT&Date">
    <img src="https://api.star-history.com/svg?repos=RayVentura/ShortGPT&type=Date" alt="Star History Chart">
  </a>
</p>
