# Automated Dataset Balancing and YOLO Training Pipeline

This repository contains an end-to-end pipeline designed to automatically balance underrepresented classes in any dataset, apply the necessary data augmentations, convert the dataset into YOLO-compatible format, and finally train a YOLO model. The goal is to streamline object detection tasks by ensuring class balance and optimal training performance.

---

## Overview

In many real-world datasets, some classes are underrepresented, which can hinder the performance of object detection models. This pipeline tackles that challenge by:
- **Analyzing class distributions** using statistical metrics.
- **Identifying underrepresented classes** automatically.
- **Generating augmented samples** to balance the dataset.
- **Converting the dataset** to YOLO format with proper label annotations.
- **Training a YOLO model** (e.g., YOLOv8) on the balanced dataset.

---

## Features

- **Automated Underrepresented Class Detection:**  
  Uses statistical metrics to identify classes that do not have sufficient representation.
  
- **Tailored Data Augmentation:**  
  Applies augmentation techniques (e.g., flipping, rotation, scaling) to boost sample counts for minority classes.
  
- **Seamless YOLO Dataset Conversion:**  
  Automatically organizes images and generates YOLO-compatible label files.
  
- **End-to-End Training Pipeline:**  
  Trains a YOLO model on the augmented and balanced dataset, outputting the best performing model weights.
  
- **Modular and Customizable:**  
  Easily configurable for different datasets and augmentation strategies.

---

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
