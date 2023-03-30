# Timeless Track
This is a group project for course Technologies in HCI in NCL university.
The code is for a portable device that can record and restore students memories,
The code is written in Python on a raspberry pi 4  and offers a simple GUI with 
the use of a stepper motor, a pi camera, an LCD touch screen, an RFID reader and a mic and headphones for recording and listening respectivly.

<img width="350" alt="image" src="https://user-images.githubusercontent.com/113771757/228869070-be790ab3-26c0-4488-ae8b-9a92998f54d8.png"> <img width="350" alt="image" src="https://user-images.githubusercontent.com/113771757/228868818-396b04ce-0696-436b-8e24-dcc18ed490ad.png">


see link for more detail:
https://vimeo.com/811275617

## General Info
In this project, we present a portable memory recording device inspired by a vintage vinyl player designed to enable students to capture their memories and create their own ‘footprint’ as Newcastle University students. A Raspberry Pi powers the device and features a camera module, microphone, speaker, stepper motor and an RFID reader enclosed in a wooden turntable design. The custom software offers a user-friendly interface for easy recording of audio and picture memories, which students can only view after graduation.
![GroupB](https://user-images.githubusercontent.com/113771757/228863813-8677f953-5733-4772-982e-05030dd3cf6e.jpeg)

## Technologies
### Hardware:
* Raspberry Pi
* Stepper motors
* RFID
* Camera
* Earphone
* Microphone
### Software:
* Python 3.7.2
### Libraries:
* tkinter
* picamera
* python.time
* python.os
* python.wave
* python.threading
* pygame
* RPI.GPIO
* mfrc522
* python.sys

## Setup
To run this project,
* Install all Libraries.
* Clone all the code folder onto the Raspberry Pi. Improtant: users should clone the code and the images to folder, because the name of the image that the program needs to initialise before it can run
* Check that the headset, microphone and camera are successfully connected
* Check if the stepper motor is successfully connected, stepper motor pins 29, 31, 33, 35
* Run the software and use the touch screen for control
