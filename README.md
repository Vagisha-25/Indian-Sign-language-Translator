# Real-Time Indian Sign Language Translator 🤟

An AI-powered communication aid that recognizes Indian Sign Language gestures and converts them into text and speech.

## About the Project

This project combines computer vision and deep learning to recognize hand gestures in real time. It converts recognized signs into text, generates sentences, and provides bilingual speech output in English and Hindi.

## Features

- Real-time hand landmark detection using MediaPipe
- Gesture recognition using an LSTM model
- Sentence generation from recognized signs
- English and Hindi translation
- Text-to-speech output
- Webcam-based interaction

## Technologies Used

- Python
- OpenCV
- MediaPipe
- TensorFlow and Keras
- LSTM
- NumPy
- deep-translator
- gTTS and pygame

## How It Works

1. Capture video through a webcam.
2. Detect hand landmarks using MediaPipe.
3. Extract numerical landmark sequences from consecutive frames.
4. Predict gestures using an LSTM model.
5. Convert recognized gestures into text and sentences.
6. Translate the text and generate speech.

## Project Highlights

- Uses numerical hand landmarks instead of raw images as model input.
- Combines gesture recognition with sentence generation.
- Integrates translation and bilingual speech output.

## Repository Structure

This public repository contains project information and demonstration materials. The complete source code, trained models, and dataset are maintained separately in a private repository.

## Future Improvements

- Expand the vocabulary of recognized signs.
- Improve recognition under different lighting conditions.
- Enhance sentence formation and recognition accuracy.

