# YOLOv9 Grad-CAM Heatmap Generator
This project is built upon the work of Jiacheng Ji and their YOLOv9-GradCAM implementation. 

# Enhanced Functionality
While the original implementation focused on generating Grad-CAM heatmaps for YOLOv9 models, this enhanced version adds the capability to automatically run all major Grad-CAM variants on your images:

GradCAMPlusPlus

GradCAM

XGradCAM

EigenCAM

HiResCAM

LayerCAM

RandomCAM

EigenGradCAM

# Key Features
Comprehensive Method Comparison: Automatically generates heatmaps using all eight Grad-CAM methods

Organized Output Structure: Results are saved in separate directories for each method

Easy Configuration: Simple parameter setup for model paths, layers, and confidence thresholds

Batch Processing: Supports processing of both single images and directories of images

# Usage
python
Simply run the script to process all images in your test directory
`
python yolov9_heatmap.py
`
The script will automatically:

Load your YOLOv9 model

Process all images in the specified directory

Generate heatmaps using all eight Grad-CAM methods

Save results in organized subdirectories

# Requirements
PyTorch

OpenCV

Ultralytics YOLO

pytorch-grad-cam

NumPy

# Acknowledgments
This work builds upon the excellent foundation provided by Jiacheng Ji's YOLOv9-GradCAM implementation. We thank the original author for their contribution to the community.
