# Human Pose Estimation App 
An interactive Streamlit-based application to estimate human poses using MediaPipe. Perfect for real-time pose detection, augmented reality, and human activity analysis.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Installation](#installation)
- [Future Enhancements](#future-enhancements)

---

## Introduction
The **Human Pose Estimation App** is built to estimate key points of a human body from uploaded images, videos, or real-time webcam streams. This application uses the **MediaPipe** framework for pose detection and renders the pose skeleton with connection lines and landmarks in images or video frames.

---

## Features
- Upload images and videos for pose estimation.  
- Use your webcam for real-time pose detection.  
- Interactive user interface powered by Streamlit.  
- Detailed visual representation of poses with key point detection.  

---

## Demo
Here’s a glimpse of the application in action:

![Demo](OutPut-image.png)

---

## Technologies Used
- **Python**: Primary programming language used to build the application.
- **Streamlit**: For creating the interactive user interface.
- **OpenCV**: For processing images and videos.
- **MediaPipe**: For human pose detection.
- **NumPy**: For numerical operations.
- **Pillow**: For image handling.

---

## How to Use

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/human-pose-estimation-app.git
   cd human-pose-estimation-app
   ```

2. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app:**
   ```bash
   streamlit run app.py
   ```

### Using the App

1. **Launch the Application**: Run the Streamlit app using the above command.
2. **Choose a Mode**: From the sidebar, select one of the following options:
   - **About**: Learn more about the purpose of the app and pose estimation technology.
   - **Upload Image**: Upload an image file to analyze pose estimations.
   - **Use Webcam**: Activate your webcam to perform real-time pose detection.
   - **Upload Video**: Upload a video file and process it frame by frame for pose estimation.
3. **View Results**: Visualize the key points and skeleton overlay on the images, videos, or webcam feed.
4. **Stop Webcam**: Use the "Stop Webcam" button to terminate the webcam feed safely.

---

## Future Enhancements
- Add support for **multi-person pose estimation**.
- Provide downloadable **reports** or processed images/videos.
- Enhance the **UI** with advanced visualizations and better user interactivity.
- Optimize performance to handle **large video files** more efficiently.
- Introduce a **pre-trained activity recognition model** for extended analysis.

---

### Author
Developed by **Priyanka Balla**.


