# Marine Pollution Detection using YOLOv8

This project focuses on detecting and classifying different types of marine waste using the YOLOv8 object detection algorithm. The system identifies waste materials such as plastic, glass, cardboard, and metal in ocean environments by applying computer vision techniques. The model was trained and deployed using Roboflow with a custom-labeled dataset.

# Project Overview

- Object detection model based on YOLOv8.
- Trained on a custom-labeled dataset using Roboflow.
- Identifies and classifies marine waste with bounding boxes and confidence scores.
- Supports multiple waste categories including plastic, glass, cardboard, metal, and etc.

# Dataset and Training

- Dataset manually labeled with bounding boxes and class labels.
- Training conducted using Roboflow with YOLOv8 integration.
- Model optimized for detecting multiple waste types in diverse ocean scenes.

# Technologies Used

- Python  
- YOLOv8 (Ultralytics)  
- Roboflow (for labeling, training, deployment)  
- OpenCV  
- Jupyter Notebook / Google Colab
# Dataset Used
https://app.roboflow.com/shobika-m/neural-ocean-db3sk/browse

# Sample Output 
Detected: Plastic (confidence: 94.2%)
Detected: Cardboard (confidence: 87.6%)


# Future Improvements

- Integrate real-time detection via drone or underwater camera feeds.
- Develop a user-friendly web or mobile interface.
- Generate location-based pollution maps using GPS-tagged image inputs.


