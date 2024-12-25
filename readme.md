# Animal Detection and Tracking System

## Overview
This project presents a comprehensive system for detecting, analyzing, and tracking animals. It integrates cutting-edge techniques and models to provide accurate results across three main functionalities:

### 1. Animal Detection from Images and Videos
   - **Techniques Used:**
     - Haar Feature-based Cascade Classifier
     - YOLO (You Only Look Once)
   - **Description:** This module detects animals in images and videos. Haar features facilitate structured pattern recognition, while YOLO enables real-time and efficient object detection.

### 2. Animal Mood Detection from Audio
   - **Techniques Used:**
     - Custom-trained machine learning model
     - Dataset provided ("animal_mood_dataset")
   - **Model Outputs:**
     ![alt text](<model accuracy outputs.png>)
   - **Description:** This component analyzes animal vocalizations to infer emotional states (e.g., happy, stressed) using a machine learning model trained on the provided dataset.

### 3. Animal Movement Tracking
   - **Techniques Used:**
     - Breadth-First Search (BFS)
     - Depth-First Search (DFS)
   - **Description:** This feature tracks animal movements within a predefined area using BFS and DFS algorithms, offering systematic exploration and navigation.

## Instructions
1. **Setup Environment:**
   - Ensure compatibility with the specified Python version and libraries.

2. **Data Preparation:**
   - Store image and video files for detection in the designated directory.
   - Save audio files for mood detection in the required format.
   - Use the provided "animal_mood_dataset" for training or fine-tuning the mood detection model if necessary.

3. **Running the Modules:**
   - **Animal Detection:** Execute the respective script for Haar or YOLO-based detection.
   - **Animal Mood Detection:** Load the custom-trained model and run the script to analyze audio inputs.
   - **Animal Movement Tracking:** Implement BFS/DFS algorithms to track and visualize animal positions.

## Project Structure
- `animal_mood_dataset/`: Dataset for training and testing the mood detection model.
- `AI_ES_CCP.ipynb`: Jupyter Notebook containing scripts, models, and visualizations.

## Dependencies
- Python 3.x
- OpenCV
- TensorFlow or PyTorch
- NumPy
- Matplotlib

## Notes
- Ensure proper placement of all data files to avoid runtime errors.
- Consult the comments in the Jupyter Notebook for in-depth explanations of the code.

---
**Developed by Abdul Basit**

