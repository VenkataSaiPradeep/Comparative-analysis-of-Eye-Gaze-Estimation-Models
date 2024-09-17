# Comparative Study and Analysis of Eye Gaze Estimation Models: iTracker, ODABE, and FAZE

## 📌 Overview

This repository presents a comparative study of three prominent eye gaze estimation models: **iTracker**, **ODABE**, and **FAZE**. Eye gaze estimation plays a crucial role in various applications, including human-computer interaction, assistive technologies, and virtual reality. Our objective is to analyze the performance, accuracy, and generalization capability of these models under various conditions.

## ✨ Models in Focus

1. **iTracker**: A CNN-based approach that utilizes head pose and eye images for gaze prediction, designed for consumer-grade devices.
2. **ODABE**: A robust, deep-learning-based model that uses multi-view geometry for accurate gaze prediction across a wide range of head poses and lighting conditions.
3. **FAZE**: A cutting-edge few-shot learning-based model designed to generalize to new users with minimal calibration data.

## 🛠️ Features

- **Data Preprocessing**: Includes scripts for preparing datasets from widely used benchmarks such as GazeCapture and MPIIGaze.
- **Model Implementation**: Reproduces the original architectures of iTracker, ODABE, and FAZE for side-by-side comparison.
- **Performance Metrics**: Evaluation using metrics such as Mean Angular Error (MAE) and inference speed under different hardware setups.
- **Visualization Tools**: Heatmaps and error distribution graphs for intuitive understanding of model behavior.

## 📊 Key Findings

- **Accuracy**: Comparison of average gaze estimation error across models.
- **Generalization**: Performance of each model on unseen users and environments.
- **Computation**: Evaluation of inference time and resource consumption.

