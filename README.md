# CVZONE_HandTraking

# Hand Tracking Module

This repository contains a Hand Tracking Module using the Mediapipe library. It detects hands in real-time using a webcam, identifies landmarks, counts the number of fingers up, and calculates distances between specific points.

## Features

- Real-time hand detection
- Identification of landmarks
- Counting the number of fingers up
- Calculation of distances between points on the hand
- Drawing landmarks and bounding boxes on the image

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Rakesh0207Kumar/HandTrackingModule.git
    cd HandTrackingModule
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

Run the script to start hand tracking:
```sh
python HandTrackingModule.py
