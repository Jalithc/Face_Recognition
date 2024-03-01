# Real-Time Face Recognition using OpenCV

This project demonstrates real-time face recognition using OpenCV in Python.

## Requirements

- Python 3.x
- OpenCV
- haarcascade_frontalface_default.xml (pre-trained face detection model, included with OpenCV)

## How it works

1. The script initializes the camera and loads the pre-trained face detection model.
2. It continuously captures frames from the camera.
3. Each frame is converted to grayscale and then processed for face detection.
4. Detected faces are highlighted with rectangles.
5. The processed frame is displayed in real-time.
6. Pressing 'q' quits the application.
