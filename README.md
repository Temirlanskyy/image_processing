# Raspberry Pi Facial Recognition

## Overview

This file is tutorial with instructions to install dependencies and for implementing facial recognition on a Raspberry Pi using Python, OpenCV, and face_recognition.

## Prerequisites

- Raspberry Pi 3
- Power supply, microSD card, keyboard, mouse, monitor, HDMI cable (for Raspberry Pi)
- USB Webcam

## Part 1: Install Dependencies for Raspberry Pi Facial Recognition

1. install opencv

>[here is a tutarial for opencv installation](https://pyimagesearch.com/2017/09/04/raspbian-stretch-install-opencv-3-python-on-your-raspberry-pi/)

2. install face_recognition
>pip install face-recognition

3. imutils
>pip install impiputils

4. gpio
> pip install RPi.GPIO

## Part 2: Train the Model and start face recognition

1. create file and copy the code
> git clone

2. in folder named dataset create folder with name and paste photo of person inside

3. Go back and run the following command
>python train_model.py

4. now after you trained your model start the main code thatonce detects face in dataset, moves servo motor 
>python facial_req.py
