# Voice Assistant - JARVIS

A Python-based voice assistant that provides comprehensive functionality through voice commands, inspired by the iconic JARVIS from Iron Man.

## Overview

This voice assistant offers natural voice interaction with capabilities ranging from basic information retrieval to system operations and entertainment features. Built with Python, it utilizes speech recognition and text-to-speech technologies to create a seamless user experience.

## Core Functionality

- **Voice Interaction**: Real-time speech recognition and synthesized voice responses
- **Time & Date Information**: Current time and date queries
- **Web Access**: Quick launching of YouTube and Google
- **Media Playback**: Music control from local library
- **System Operations**: Screenshot capture and computer controls
- **Knowledge Access**: Wikipedia integration for factual information
- **Entertainment**: Joke telling feature

## Installation Requirements

### System Requirements
- Python 3.7 or newer
- Windows operating system (primary support)
- Functional microphone and speakers

### Required Python Packages
```bash
pip install pyttsx3 speechrecognition wikipedia-api pyautogui pyjokes
```

### Additional System Requirements
- pyaudio package for microphone functionality
- Windows Media Player for music playback

## Usage Instructions

1. Launch the application:
```bash
python ujjawal.py
```

2. Wait for the initialization and welcome message

3. Available voice commands include:

### Information Commands
- "what time is it" - Current time
- "what's the date" - Current date
- "wikipedia [topic]" - Wikipedia search
- "tell me a joke" - Random joke

### Media & Web Commands
- "play music" - Random song from Music folder
- "play music [song name]" - Specific song playback
- "open youtube" - Launch YouTube
- "open google" - Launch Google

### System Commands
- "screenshot" - Capture screen
- "change your name" - Rename assistant
- "shutdown" - Shutdown computer
- "restart" - Restart computer
- "offline" or "exit" - Close application

## Configuration

### Customization Options
- Voice parameters including type, speed, and volume
- Assistant name modification
- File path adjustments for music and screenshots

### File Structure
- assistant_name.txt - Stores custom assistant name
- ujjawal.py - Main application file

## Technical Architecture

- Speech Recognition: Google Speech Recognition API
- Text-to-Speech: pyttsx3 engine
- Voice Processing: Real-time microphone input with timeout management
- Error Handling: Comprehensive exception management

## Platform Support

- Primary: Windows 10/11
- Limited support for other platforms with path modifications

## Troubleshooting Guide

### Common Issues

1. Microphone Detection Problems
   - Verify microphone permissions
   - Check if microphone is occupied by other applications

2. Speech Recognition Issues
   - Ensure stable internet connection for Google Speech API
   - Minimize background noise and speak clearly

3. Module Import Errors
   - Confirm all dependencies are properly installed
   - Update outdated packages using pip install --upgrade

### Performance Recommendations
- Operate in low-noise environments for optimal speech recognition
- Maintain reliable internet connection for web-based features
- Organize music files systematically in the Music folder

## Development Information

### Feature Expansion
1. Implement new command recognition in main loop
2. Develop corresponding functionality
3. Incorporate error handling and voice feedback

### Code Organization
- Modular function architecture
- Type hints for code clarity
- Comprehensive error handling

## License

This project is open source under the MIT License.

## Contribution

Contributions are welcomed through pull requests or issue reporting for bugs and feature suggestions.

## Important Notice

This assistant utilizes external services including Google Speech Recognition and Wikipedia. Please ensure compliance with their respective terms of service. Exercise caution with shutdown/restart commands as they immediately affect system operation.

Created with Python and AI enthusiasm.
