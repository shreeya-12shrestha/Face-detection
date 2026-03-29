# 🎭 Face Detection

Real-time face detection using Python and OpenCV with Haar Cascade classifier.

## How It Works

- Opens **live webcam feed**
- Detects **faces in real-time** using Haar Cascade algorithm
- Draws a **rectangle** around each detected face

## Built With

- [Python](https://python.org)
- [OpenCV](https://opencv.org) — webcam feed & face detection
- Haar Cascade Classifier (`haarcascade_frontalface_default.xml`)

## Installation
```bash
pip install opencv-python
```

## Run
```bash
python facedetection.py
```

> Press **ESC** or **Q** to exit.

## Project Structure
```
facedetection/
│
├── facedetection.py                    # Main script
├── haarcascade_frontalface_default.xml # Face detection model
└── README.md
```

## Notes

- Make sure your **webcam is connected**
- Works best in **good lighting**
- Can detect **multiple faces** simultaneously
