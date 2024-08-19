# Autonomous-Wildlife-Monitoring-System

### Overview
The Autonomous Wildlife Monitoring System is designed to detect, track, and analyze wildlife through video and sound detection.This system uses advanced computer vision and audio processing. It's perfect for wildlife research, conservation efforts, and security purposes.

### Features

#### 1. Video Detection
- Identifies animals like Zebra,Giraffe,Bear and Elephant in video frames and images using Haar Cascade and YOLO. OpenCV handles video processing and annotation, while Google Colab Patches enable frame display within Jupyter notebooks.

#### 2. Sound Detection
- Analyzes and classifies sounds, including animal noises like zebra ,bear and etc , with techniques like audio normalization, visualization, and emotion-based color coding. An animal mood classifier provides insights into emotional states.

#### 3. Animal Interaction Analysis
- Uses graph-based algorithms like Dijkstra's Algorithm to analyze spatial relationships between animals, measuring distances and visualizing interactions using Matplotlib. This helps in understanding animal positions and movements.

### Technologies Used
- Computer Vision: OpenCV, Haar Cascade, YOLOv8
- Audio Processing: Librosa for reading and normalizing audio files
- Visualization: Matplotlib for audio signal visualization.
