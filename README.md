# HANDY-hand-gesture-recognition-system
Certainly! Here is the `README.md` file for your code:

---

# Hand Gesture Recognition using MediaPipe and TensorFlow

This repository contains a Python script for real-time hand gesture recognition using MediaPipe and TensorFlow. The code captures webcam frames, processes them to detect hand landmarks using the MediaPipe library, and predicts the corresponding gestures using a pre-trained TensorFlow model.

## Prerequisites

Make sure you have the following libraries installed in your Python environment:

- OpenCV (`cv2`)
- NumPy (`numpy`)
- MediaPipe (`mediapipe`)
- TensorFlow (`tensorflow`)

You can install these libraries using `pip`:

```bash
pip install opencv-python numpy mediapipe tensorflow
```

## Model and Class Names

- The pre-trained gesture recognition model (`mp_hand_gesture`) is loaded using TensorFlow's Keras API. Make sure to place the model file in the project directory.

- The class names corresponding to the gestures are loaded from the `gesture.names` file. Each line in this file represents a class name. Ensure the file contains the correct class names for the gestures your model recognizes.

## Configuration

You can adjust the following parameters in the `main.py` file:

- `max_num_hands`: Maximum number of hands to detect (default is 1).
- `min_detection_confidence`: Minimum confidence value ([0.0, 1.0]) to consider a hand landmark detection as successful (default is 0.7).

## Keyboard Shortcut

- Press `q` to quit the application and close the webcam feed.

---
