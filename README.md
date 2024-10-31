# Testimony Based Criminal Sketch Generator

## Overview
The **Testimony Based Criminal Sketch Generator** is a project developed to aid forensic investigations by transforming eyewitness audio testimonies into visual representations.

## Features
- **Audio Transcription**: Utilizes the Whisper model to transcribe raw audio files of eyewitness testimonies.
- **Feature Extraction**: Leverages the LLaMA model to extract critical features from the transcriptions.
- **Sketch Generation**: Employs Stable Diffusion to create police sketches based on the extracted features.
- **Customizable Posters**: Allows investigators to add disguises and generate customizable posters.

## Technologies Used
- **Whisper**: For audio transcription.
- **LLaMA**: For extracting features from the transcriptions.
- **Stable Diffusion**: For generating police sketches.
- **Python**: Programming language for implementation.
- **FastAPI**: Framework for building the application.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/USERNAME/REPO_NAME.git
    cd REPO_NAME
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    uvicorn backend:app --host 0.0.0.0 --port 8000
    ```

## Usage
Upload an MP3 file to generate a police sketch based on the testimony.
