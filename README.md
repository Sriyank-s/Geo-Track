# GeoTrack AI

**Internship Project: Jan 2024 - May 2024**  
**Topic:** Computer Vision & Deep Learning

## Project Overview
**Objective:** Develop a computer vision and deep learning system for aerial image analysis, object detection, and human identification in surveillance applications.

This project focuses on analyzing aerial imagery using YOLOv8 and geospatial data, along with gait-based deep learning models for human recognition and anomaly detection. The aerial dataset includes over 100,000 GeoTIFF images, while gait recognition utilizes CASIA-B and OU-ISIR datasets with over 500,000 samples. The system supports real-time surveillance and provides actionable insights through an interactive OSRM-based dashboard for visualization, geolocation mapping, and dynamic analytics.

## Key Components

### 1. Aerial Object Detection
- **Dataset:** Over 100,000 labeled aerial images.
- **Model:** YOLOv8 for object detection and classification.
- **Geospatial Integration:** GeoTIFF data was used to enable precise geolocation mapping.
- **Dashboard:** An interactive dashboard integrating OSRM supported real-time tracking, object visualization, and dynamic analytics for aerial surveillance applications.

### 2. Gait-Based Human Identification
- **Dataset:** CASIA-B and OU-ISIR datasets, totaling over 500,000 video frames.
- **Model:** Deep learning model trained on motion sequences segmented into spatiotemporal patches for enhanced feature extraction.
- **Real-Time Implementation:** Integrated with OpenCV and TensorRT to accelerate inference.
- **Performance:** Achieved robust accuracy in distinguishing normal from suspicious behavior during live monitoring.

## Challenges and Solutions
- **Large-scale data handling:** Optimized data pipelines ensured smooth processing of 100k+ aerial images.
- **Real-time performance:** TensorRT integration reduced latency for live video analysis.
- **Data diversity:** Spatiotemporal segmentation improved gait recognition for varied human motion patterns.

## Key Insights
- Combining geospatial data with deep learning significantly enhances object localization accuracy.
- Real-time dashboards provide actionable insights for surveillance operations.
- Gait-based recognition is effective for anomaly detection in live monitoring systems.

## Conclusion
GeoTrack AI demonstrates how computer vision, deep learning, and geospatial data integration can produce actionable intelligence for aerial surveillance and human identification tasks. While the underlying code is proprietary due to company policy, this README documents the methodology, results, and key learnings from the project.
