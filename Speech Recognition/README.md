# Automatic Speech Recognition with OpenAI Whisper

This repository provides a simple pipeline for automatic speech recognition (ASR) using OpenAI's Whisper model. 
The script checks for GPU availability, installs necessary packages, downloads an audio file, plays it, and performs speech recognition to transcribe the audio content.

## Table of Contents

- Prerequisites
- Installation
- Usage
- Contributing
- License

### Prerequisites

- NVIDIA GPU with CUDA installed (optional, but recommended for faster processing)
- Python 3.6 or higher
- Internet connection to download the audio file and dependencies

### Installation

Clone the repository:

````
git clone https://github.com/Lala2398/Deep_Learning.git
ls
cd Speech Recognition
````

Create a virtual environment : 

````
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
````

Install the [required packages:](https://github.com/Lala2398/Deep_Learning/blob/main/Speech%20Recognition/requirements.txt)

````
requirements.txt
````

### Usage

Run the [script](https://github.com/Lala2398/Deep_Learning/blob/main/Speech%20Recognition/OpenAIWhisper_HuggingFaceTransformers.ipynb) to perform speech recognition:

````
OpenAIWhisper_HuggingFaceTransformers.ipynb

````

This script will:

- Check for NVIDIA GPU status
- Install necessary packages
- Download an audio file
- Play the audio file
- Transcribe the audio using the Whisper model
- Print the transcribed text

### Using Google Colab

You can also use the notebook with Google Colab for a convenient cloud-based environment. Follow these steps:

- Open the notebook [OpenAIWhisper_HuggingFaceTransformers.ipynb](https://github.com/Lala2398/Deep_Learning/blob/main/Speech%20Recognition/OpenAIWhisper_HuggingFaceTransformers.ipynb) in Google Colab.
- Ensure your runtime type is set to use a T4 GPU for optimal performance. To do this:
- Go to the Runtime menu.
- Select Change runtime type.
- In the Hardware accelerator dropdown, select GPU T4.

This setup will ensure that the notebook runs efficiently using Google's T4 GPUs.


### Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

### License

This project is licensed under the [MIT License](https://github.com/Lala2398/Deep_Learning/blob/main/Speech%20Recognition/LICENSE). See the LICENSE file for details.
