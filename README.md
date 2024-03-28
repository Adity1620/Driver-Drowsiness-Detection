# Driver Drowsiness Detection

## Introduction

This project aims to detect driver drowsiness in real-time using various machine learning and computer vision techniques. It utilizes different datasets and models to achieve accurate detection of drowsiness, ensuring road safety.

## Datasets Used

1. **MRL Eye Dataset**
   - **Context:** Contains infrared images of human eyes captured under various conditions.
   - **Features:** Gender, glasses, eye state, reflections, lighting conditions, sensor ID.
   - **Citation:** [4D: A Real-Time Driver Drowsiness Detector Using Deep Learning](https://www.researchgate.net/publication/352016153_4D_A_Real-Time_Driver_Drowsiness_Detector_Using_Deep_Learning)
   - **Dataset Link:** [Gender, glasses, eye state, reflections, lighting conditions, sensor ID.](https://www.kaggle.com/datasets/imadeddinedjerarda/mrl-eye-dataset)

2. **Driver Drowsiness Dataset (DDD)**
   - **Context:** Extracted and cropped faces of drivers from real-life videos.
   - **Features:** RGB images, Drowsy & Non-Drowsy classes, image size 227x227.
   - **Citation:** [Detection and Prediction of Driver Drowsiness for the Prevention of Road Accidents Using Deep Neural Networks Techniques](https://doi.org/10.1007/978-981-33-6893-4_6)
   - **Dataset Link:** [Dataset-kaggle](https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd)

3. **YOLOv5 Datasets**
   - Custom datasets for object detection using YOLOv5 architecture.

## Code Overview

### 1. CNN + Haar Cascade Using MRL Dataset
- Python script for detecting eye state (open/close) using CNN and Haar cascade.
- Utilizes MRL Eye Dataset for training and testing.

### 2. CNN Using DDD Dataset
- Python script for training a CNN model to classify driver drowsiness using the DDD dataset.

### 3. YOLOv5 Using Dataset 1 & 2
- Utilizes YOLOv5 for object detection on custom datasets for drowsiness detection.

## Usage

1. Clone the repository.
2. Install required dependencies.
3. Run the respective scripts for drowsiness detection using different techniques.
4. Ensure appropriate datasets are available for training and testing.
5. Adjust parameters as needed for your specific use case.

## Conclusion

The project showcases multiple approaches to driver drowsiness detection, leveraging machine learning and computer vision techniques. By combining various datasets and models, it provides a comprehensive solution for real-time detection and prevention of drowsy driving, ultimately contributing to road safety.

## Contributors
1. CH Sri Cheran - sricharan320@gmail.com
2. Aditya V - adityavenkatesh16@gmail.com
