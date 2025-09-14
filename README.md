# GeoTrack AI

**Internship Project: Jan 2024 - May 2024**  
**Topic:** Computer Vision & Deep Learning

## Project Overview
**Objective:** Develop a computer vision and deep learning system for aerial image analysis, object detection, and human identification in surveillance applications.

This project focuses on analyzing aerial imagery using YOLOv8 and geospatial data, along with gait-based deep learning models for human recognition and anomaly detection. The aerial dataset includes over 100,000 GeoTIFF images, while gait recognition utilizes CASIA-B and OU-ISIR datasets with over 500,000 samples. The system supports real-time surveillance and provides actionable insights through an interactive OSRM-based dashboard for visualization, geolocation mapping, and dynamic analytics.

## Key Steps in the Project

The datasets used for this project consisted of:

1. **Aerial Image Dataset:** Over 100,000 labeled GeoTIFF images for object detection and classification.  
2. **Gait Recognition Dataset:** CASIA-B and OU-ISIR datasets with over 500,000 video frames for human identification and anomaly detection.

### 1. Data Preparation

**Preprocessing (Aerial Images):**  
- Standardized all images to a uniform resolution and extracted geospatial information from GeoTIFF files.  
- Removed corrupted or incomplete images to ensure dataset quality.  
- Split data into training, validation, and testing sets to enable robust model evaluation.

**Preprocessing (Gait Recognition):**  
- Video frames were extracted and motion sequences segmented into spatiotemporal patches.  
- Normalized and resized images to fit model input requirements.  
- Data augmentation applied to improve generalization, including rotation, flipping, and scaling.

**Transformation and Storage:**  
- Aerial images and gait video frames were stored in structured directories for easy model integration.  
- Metadata including geolocation, timestamps, and labels were stored in CSV files for indexing and analysis.

---

### 2. Exploratory Data Analysis (EDA)

**Aerial Image Analysis:**  
- Distribution of object classes analyzed to check for class imbalance.  
- Spatial distribution of detected objects visualized to ensure geospatial coverage.

**Gait Dataset Analysis:**  
- Analyzed motion sequence lengths and frame quality to remove anomalies.  
- Checked label distribution for normal versus suspicious behavior sequences.  

**Visualization and Insights:**  
- Heatmaps and scatter plots visualized object locations across geospatial coordinates.  
- Histograms of gait sequence lengths helped determine optimal input sequence size for the model.  
- Insights guided model input preprocessing and dataset balancing strategies.

---

### Key Visualizations

- **Aerial Object Distribution:** Maps showing frequency and location of detected object classes.  
- **Gait Sequence Analysis:** Box plots and histograms illustrating motion sequence lengths and variance.  
- **Dashboard Snapshots:** Interactive visualizations showing real-time object tracking and geolocation mapping.

**Findings and Insights:**  
- Spatial integration of GeoTIFF data improved object localization accuracy.  
- Preprocessing and segmentation of gait sequences enhanced model learning for human recognition.  
- Class imbalance in aerial objects and gait behaviors was addressed via dataset augmentation to ensure fair model training.

**Conclusion:**  
The EDA and preprocessing provided critical insights into both aerial imagery and gait data, allowing for effective model development. By understanding dataset characteristics, preprocessing steps were tailored to optimize YOLOv8 object detection and deep learning gait recognition for accurate real-time surveillance.


## Challenges and Solutions

- **Large-scale data handling:** Optimized data pipelines ensured smooth processing of 100,000+ aerial images.  
- **Real-time performance:** TensorRT integration reduced latency for live video analysis.  
- **Data diversity:** Spatiotemporal segmentation improved gait recognition for varied human motion patterns.  
- **GeoTIFF Coordinate Extraction:** Extracting geospatial coordinates from GeoTIFF files required careful preprocessing to ensure accurate object localization.  
- **Image and Video Quality:** Ensuring consistent quality across aerial images and video frames was critical for reliable model performance.  
- **Class Imbalance:** Addressed using data augmentation and careful dataset splitting to ensure fair model training.


## Key Insights

1. **Integration of Geospatial Data and Deep Learning:**  
   Incorporating geospatial coordinates from GeoTIFF files into the YOLOv8 object detection pipeline significantly improved object localization and mapping accuracy. By leveraging geospatial metadata, the model was able to not only detect objects but also accurately place them on real-world coordinates, enabling precise tracking and spatial analysis for aerial surveillance applications.

2. **Real-Time Dashboards for Actionable Insights:**  
   The interactive OSRM-based dashboard provided a visual interface to monitor detected objects and human activities in real time. Operators could track object movement, assess spatial patterns, and identify anomalies instantly. The dashboard allowed dynamic querying and visualization, transforming raw data from aerial imagery and video feeds into actionable insights for operational decision-making.

3. **Gait-Based Recognition for Human Anomaly Detection:**  
   The gait recognition model, trained on large datasets (CASIA-B and OU-ISIR), proved highly effective in identifying normal versus suspicious behavior. Spatiotemporal segmentation of video frames enhanced feature learning, allowing the model to detect subtle motion patterns that distinguish anomalous activities. This approach ensured robust performance in live surveillance, with accelerated inference provided by TensorRT integration.

4. **Handling Large-Scale and Diverse Data:**  
   Processing over 100,000 aerial images and 500,000+ gait video frames required optimized pipelines and careful preprocessing. Addressing challenges such as inconsistent image quality, varying lighting conditions, and motion artifacts was crucial. Preprocessing steps—including normalization, resizing, and augmentation—ensured the data fed into the models was of high quality and representative of real-world scenarios.

5. **Insights on Model Deployment and Scalability:**  
   Deploying the models in a real-time environment highlighted the importance of optimization for latency reduction. Combining TensorRT with efficient data loading allowed the system to process high-volume data streams without sacrificing accuracy, ensuring that the surveillance and tracking system could scale effectively to real-world applications.


## Conclusion

GeoTrack AI demonstrates how computer vision, deep learning, and geospatial data integration can produce actionable intelligence for aerial surveillance and human identification tasks. Due to restrictions from the company and since all rights belong to my organization, I am unable to provide the code or images from this project. This README, however, documents the methodology, results, and key learnings in detail, highlighting the project’s outcomes and insights while respecting company policies.

