# Human-Object_Detection


## Description
This project demonstrates **Human and Object Detection** using **OpenCV** and **Darknet** with pre-trained models. The system is capable of detecting various objects and humans in static images, webcam feeds, and live video streams.

The model uses **YOLO (You Only Look Once)** for object detection, a real-time object detection system that is capable of identifying and classifying objects within an image or video. This project leverages OpenCV for image and video processing, and it integrates with a **Darknet helper** to use the YOLO model for detecting various objects and humans.

## Key Features
- **Human Detection** in both static images and real-time webcam feeds.
- **Object Detection** using YOLO model for multiple object types.
- **Bounding Box Visualization** around detected objects and humans.
- **Real-Time Video Processing** using webcam feed for object detection.

## Setup

### Prerequisites
Ensure you have Python installed and the following libraries:

- **OpenCV**
- **NumPy**
- **Darknet (YOLO model)**
- **Matplotlib** (Optional, for visualization)

### Conclusion
This project leverages real-time object detection using the YOLO model for various human and object detection tasks. It's highly efficient and can be used in various fields such as:
- Surveillance
- Security
- Human-computer interaction
By utilizing YOLO, this system is capable of identifying objects and humans in real-time with high accuracy, offering potential applications in numerous industries.

### Future Work
- Integration of multiple object detection models to enhance detection accuracy.
- Real-time face recognition and action recognition in videos.
- Embedded system deployment (e.g., Raspberry Pi) for live detection.
- Improve detection for small objects and occlusions in real-time applications.

  
You can install the required libraries using `pip`:
```bash
pip install opencv-python numpy matplotlib

