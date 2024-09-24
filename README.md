# face-detection-opencv
This Face Detection System uses OpenCV to identify faces in real-time through webcam input. Leveraging Haar Cascade Classifier, it captures video frames, converts them to grayscale, and detects faces, drawing rectangles around them. 

# Face Detection System Using OpenCV

This repository contains a simple face detection system implemented in Python using OpenCV. The system captures video from the webcam, detects faces in real-time, and displays the result with rectangles drawn around detected faces.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Real-time face detection using Haar Cascade Classifier.
- Captures video feed from the default webcam.
- Draws rectangles around detected faces.

## Prerequisites

Make sure you have the following installed:

- Python (3.6 or higher)
- OpenCV
- NumPy

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ahmdmohamedd/face-detection-opencv.git
   cd face-detection-opencv
   ```

2. Install the required libraries:

   ```bash
   pip install opencv-python numpy
   ```

## Usage

1. Run the face detection script:

   ```bash
   python main.py
   ```

2. A window will open showing the video feed from your webcam. Rectangles will be drawn around detected faces.

3. Press 'q' to exit the application.

## Contributing

Contributions are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.
