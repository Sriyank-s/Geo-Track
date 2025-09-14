# GeoTrack AI

**Internship Project: Jan 2024 - May 2024**  
**Topic:** Computer Vision & Deep Learning

## Project Overview
GeoTrack AI focuses on aerial image analysis and human identification using advanced deep learning and geospatial techniques. The project aimed to:

- Detect and classify objects in aerial images with high precision.
- Incorporate geospatial insights for accurate mapping and object localization.
- Build a real-time surveillance and tracking system using gait-based human identification.

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
