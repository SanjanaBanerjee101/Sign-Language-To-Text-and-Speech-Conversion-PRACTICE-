Sign-Language-To-Text-and-Speech-Conversion
===========================================

**Abstract**
==============
Sign language is one of the oldest and most natural forms of communication, especially for the deaf and mute community. This project presents a real-time method using neural networks for finger-spelling based American Sign Language (ASL) recognition. It employs a convolutional neural network (CNN) to recognize hand gestures from images captured by a camera. The system processes the hand's position and orientation, applies filtering and classification, and uses calibrated images to train the CNN for accurate gesture recognition.


**Introduction**
==============
American Sign Language (ASL) is widely used by the deaf and mute community for communication. Since these individuals cannot use spoken language, sign language becomes essential for exchanging thoughts and messages visually through hand gestures. This project aims to build a model that recognizes finger-spelling gestures of ASL to form words by combining individual signs.

**Project Overview**
===================
My primary objective for this project was to deepen my understanding of real-world machine learning deployment and environment setup, learning under guidance while independently overcoming challenges.

Project Contribution:
====================

This project involved building a real-time Sign Language to Text and Speech Conversion system using deep learning and computer vision techniques. While the core idea and codebase were initially developed by others, I took on the responsibility of adapting and improving the existing code to work seamlessly on my local environment. My key contributions included:

*Resolving environment and dependency issues to ensure smooth project setup and execution.

*Creating and maintaining the requirements.txt file to manage Python package dependencies effectively.

*Customizing and optimizing code components to align with my system configuration.

*Gaining a solid understanding of the underlying concepts and workflows by independently troubleshooting and enhancing the project.

*Developing hands-on experience with key libraries such as TensorFlow, OpenCV, MediaPipe, and pyttsx3.

This practical engagement helped me deepen my knowledge of machine learning project deployment and reinforced my problem-solving skills in real-world software integration.

This repository{https://github.com/Devansh-47/Sign-Language-To-Text-and-Speech-Conversion} contains the original project developed to recognize ASL finger-spelling gestures. My contributions involved adapting the existing codebase to run successfully on my system, troubleshooting dependencies, and creating a requirements.txt file to simplify installation for other users.

**Key Features**
================
    Real-time hand gesture recognition using CNN
    Uses MediaPipe for robust hand landmark detection under varied lighting and backgrounds
    Converts recognized gestures into text and speech using pyttsx3
    User-friendly interface for communication aid

**Requirements**
================
  Python 3.9+
  Webcam
  Libraries: OpenCV, NumPy, TensorFlow, Keras, MediaPipe, pyttsx3, cvzone

**Installation**
================
To install the required Python packages, run:
    pip install -r requirements.txt


**How to Use**
==============
  Activate the virtual environment.
  Run the data collection script to gather hand gesture data.
  Train the CNN model on the collected data.
  Use final_pred.py for real-time prediction and text-to-speech conversion.

**Project Structure**
======================
  data_collection_final.py — Collects hand gesture images using MediaPipe
  train.py — Trains the CNN model on the preprocessed images
  final_pred.py — Runs real-time gesture recognition and converts text to speech
  requirements.txt — Lists all dependencies for easy setup

**System Diagrams and Flowcharts**
=================================

**System Flowchart:**

![system flowchart](https://user-images.githubusercontent.com/99630855/201490238-224f65aa-071f-473a-8c23-a9d60e0a47d8.png)
**Use-case diagram:**

![Untitled Diagram drawio](https://user-images.githubusercontent.com/99630855/201490218-85f4c194-0496-4dfb-b920-e486256bd6b7.png)
 
**DFD diagram:**

![Flowcharts (2)](https://user-images.githubusercontent.com/99630855/201490221-f543fa6d-75ba-4db0-bc35-ee8c06e25018.png)
![Flowcharts (1)](https://user-images.githubusercontent.com/99630855/201490226-966bcc44-8149-433d-ab3b-b0a23deb1c91.png)
 

**Sequence diagram:**

![sequence2](https://user-images.githubusercontent.com/99630855/201490230-b903c365-7a4c-4972-8268-5687060b9cd0.png)


**Note on My Contributions**
=============================
  While the core model and algorithms were developed by the original authors, I improved the project’s usability by:
      Resolving compatibility and dependency issues on my local machine
      Adding a requirements.txt file to streamline environment setup
      Testing and validating the code on Windows OS
      Documenting the installation and usage steps for easier replication

