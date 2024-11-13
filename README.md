# Drone and Bird Detection using Fine-Tuned YOLOv11

This repository contains code for fine-tuning the pre-trained YOLOv11 model (trained on the COCO dataset) using the Airborne Object Detection dataset. The objective is to develop a robust object detection model capable of distinguishing between drones and birds, especially in challenging environments where both may appear in the same frame.

## Project Overview

In recent years, the need for precise drone detection has grown due to concerns around security, privacy, and safety. Drones can be challenging to identify accurately, especially when birds are also present in the field of view. By leveraging the YOLOv11 model, this project aims to improve detection accuracy through fine-tuning on an airborne-specific dataset, enabling better differentiation between drones and other airborne objects like birds.

### Objectives

- Fine-tune the YOLOv11 model on the Airborne Object Detection dataset to enhance its accuracy for drone and bird detection.
- Enable reliable identification of drones in environments where both drones and birds are present.
- Provide a deployable solution for real-world drone detection, supporting applications in security and monitoring.

## Features

- **Accurate Drone Detection**: Detect drones with high precision in complex scenarios containing multiple airborne objects.
- **Bird Detection and Differentiation**: Classify and distinguish birds from drones for more reliable airborne object detection.
- **Real-time Performance**: Optimized for real-time applications, making it suitable for security and surveillance.

## Technologies Used

- **Python**: The primary programming language for model training and inference.
- **YOLOv11**: State-of-the-art object detection model, pre-trained on the COCO dataset and fine-tuned on the Airborne Object Detection dataset.
- **PyTorch**: Deep learning framework for implementing and training the YOLOv11 model.

## Datasets

- **COCO Dataset**: The initial training dataset for YOLOv11.
- **Airborne Object Detection Dataset**: A specialized dataset focused on airborne objects, including drones and birds, used for fine-tuning the model.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Drone-Bird-Detection-YOLOv11.git
   cd Drone-Bird-Detection-YOLOv11
