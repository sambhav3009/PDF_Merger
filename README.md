# Image-to-Text-to-Audio Converter 📷➡️📝➡️🔊

This is a Python project that converts text from an image to audio. The program extracts text from an image using Optical Character Recognition (OCR) and then converts the extracted text to speech using text-to-speech (TTS) functionality. This can be useful for visually impaired users or for applications where users need to hear the content of an image.

## Table of Contents
- [Features](#features)
- [How It Works](#how-it-works)
- [Requirements](#requirements)

## Features

- Extracts text from an image using Tesseract OCR.
- Converts the extracted text to audio using Google Text-to-Speech (gTTS).
- Saves the generated audio as an MP3 file.

## How It Works

1. **Image to Text**: 
   - The program uses `pytesseract` (Python wrapper for Tesseract OCR) to read text from an image file.
2. **Text to Audio**: 
   - After extracting text, the program uses `gTTS` (Google Text-to-Speech) to convert the text into an audio file.
3. **Saving Audio**:
   - The audio is saved as an MP3 file that can be played on any audio player.

## Requirements

- Python 3.x
- Install the following packages:

   ```bash
   sudo apt install tesseract-ocr
   pip install pytesseract
   pip install gTTS
   pip install Pillow==9.0.0
