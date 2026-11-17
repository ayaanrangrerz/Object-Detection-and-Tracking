# Object Detection and Tracking

A Python webcam demo that uses OpenCV and a YOLO model to draw detections and track visible objects.

## Getting started
Requires Python, OpenCV, and a compatible YOLO model/weights. Check the model path configured in `object_detection.py` and provide the required weights before launching.

```bash
python -m pip install opencv-python
python object_detection.py
```

Camera access is required for the webcam flow. Detection results depend on the model and hardware; this repository is a demonstration, not a safety or surveillance system.
