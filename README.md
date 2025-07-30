# CodeClauseInternship_Basic-Speech-Recognition

This repository demonstrates a basic speech recognition application using Python and the `speech_recognition` library. It was created as part of a CodeClause Internship project.

## Features

- Listens to audio input from microphone
- Uses Google Speech Recognition to transcribe speech
- Responds to simple commands: `"hello"` and `"goodbye"`
- Provides feedback for unrecognized words

## How It Works

The main functionality is implemented in a Jupyter Notebook (`speechRecognition.ipynb`). The script listens to the microphone, recognizes speech using Google's API, and prints responses based on the recognized command.

### Example Usage

When you say "hello", the application responds with "Hello there!".  
When you say "goodbye", it responds with "Goodbye!" and stops listening.  
For any other input, it will notify you that the word is not recognized.

## Requirements

- Python 3.9+
- `speech_recognition` library
- Microphone
