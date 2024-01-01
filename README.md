# Drowsiness Detector with Arduino, LCD, and Buzzer

![Drowsiness Detector](drowsiness_detection.gif)

## Overview
This project implements a Drowsiness Detector using computer vision techniques with Python (OpenCV and Dlib) and interfaces it with an Arduino board, LCD, and a buzzer. The system monitors facial landmarks and detects drowsiness based on eye blink patterns. When drowsiness is detected, the Arduino triggers the buzzer and displays the alert on the LCD.

## Features
- Drowsiness detection using facial landmarks
- Interface with Arduino for real-time alerts
- Integration with LCD for visual feedback
- Buzzer for audible alerts

## Hardware Requirements
1. Arduino board
2. LCD display
3. Buzzer
4. Webcam (for the computer vision part)

## Software Requirements
1. Python with OpenCV, Dlib, and imutils
2. Arduino IDE for uploading the Arduino code

## Setup Instructions

### Computer Vision Part (Python)
1. Clone the repository:
   ```bash
   git clone https://github.com/varshin5699/drowsiness-detection.git
   cd drowsiness-detection

  
