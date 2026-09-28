---
layout: page
title: Fire Classification & Detection
description: Two-stage vision-based fire detection using EfficientNet-B0 and YOLOv8
date: 2024-07-01
category: selected
chip: Smart Factory · 2024
tech: [python, efficientnet, yolov8, csharp]
---

<p class="project-meta">2024 · Python · EfficientNet-B0 · YOLOv8 · C#</p>

Developed a vision-based fire detection system combining **EfficientNet-B0 classification** and **YOLOv8 object detection** to reduce false alarms and improve fire and smoke detection from image and CCTV data.

The system first classifies input images into **fire, smoke, both, or none**, and then applies object detection to localize fire and smoke regions with bounding boxes.

## Key features

- **Two-stage detection pipeline** combining image classification and object detection
- **EfficientNet-B0 classifier** for fire, smoke, both, and normal-image classification
- **YOLOv8-based object detection** for localizing fire and smoke regions
- **23,824 images** prepared for classification and **36,383 images** for object detection
- **Data preprocessing and augmentation** using rotation, brightness, and saturation variations
- **C# WinForm application** for visualizing detection results from image and CCTV inputs
