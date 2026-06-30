# Image Recognition (Face Recognition)

## Project Description
This project is a real-time Face Recognition System built using Python, OpenCV, and the face_recognition library. It detects faces from a webcam and identifies people by comparing them with images stored in a dataset.

## Features
- Real-time face detection
- Face recognition using webcam
- Displays the person's name
- Labels unknown faces as "Unknown"

## Technologies Used
- Python
- OpenCV
- face_recognition
- NumPy

## Project Structure

Image-Recognition/
│── image1.py
│── dataset/
│   ├── Person1/
│   ├── Person2/
│── README.md

## Installation

1. Clone the repository:
```bash
git clone https://github.com/aasrithalakkamraju-hash/Image-Recognition.git
```

2. Install the required packages:
```bash
pip install opencv-python face_recognition numpy
```

3. Place your images inside the `dataset` folder.

4. Run the project:
```bash
python image1.py
```

## Output
- Detects faces from the webcam.
- Displays the recognized person's name.
- Shows "Unknown" for faces not in the dataset.

## Author
Asritha
