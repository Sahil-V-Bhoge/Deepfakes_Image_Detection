# Deepfake Detection Model

This repository contains the implementation of a deepfake detection model designed to identify and differentiate between real and manipulated images. The model leverages the ResNet50 architecture for feature extraction and has been fine-tuned to achieve high accuracy in detecting deepfakes.

## Project Overview

### 1. Model Development
- **Architecture**: The deepfake detection model is built upon the ResNet50 architecture, known for its deep layers and powerful feature extraction capabilities. ResNet50's ability to capture intricate patterns in images makes it an ideal choice for this task.
- **Fine-Tuning**: The ResNet50 model was fine-tuned on a dataset containing 0.14 million facial images. Fine-tuning was crucial in adapting the pre-trained model to the specific nuances of deepfake detection, leading to significant improvements in both performance and precision.

### 2. Model Performance
- **AUC Score**: 0.98
- **F1-Score**: 0.95 F1-score




### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/deepfake-detection.git
   cd deepfake-detection
