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
  
## 👥 Team Members
- **Venkata Sai Pradeep Nagisetti**
- **Dr. Abdallah Moubayed**
- **Pavithra Moravaneni**
- **Loka Kalyan Balla**
- **Sowmya Veldandi]** 
- **Kethan Yeddla** 
- **Sai Teja Madha**

## 📚 References
- 1.] iTracker: Eye Tracking for Everyone K. Krafka et al., “Eye Tracking for Everyone,” www.cv-foundation.org,2016.
- 2.] X. Zhang, Y. Sugano, M. Fritz, and A. Bulling, “MPIIGaze: Real-World Dataset and Deep Appearance-Based Gaze Estimation,” IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 41, no. 1, pp.162–175, Jan. 2019, doi: https://doi.org/10.1109/tpami.2017.2778103.
- 3.] S. Park, S. D. Mello, P. Molchanov, U. Iqbal, O. Hilliges, and J. Kautz,“Few-Shot Adaptive Gaze Estimation,” openaccess.thecvf.com, 2019.
- 4.] Bruno Klein Salvalaio and Gabriel, “Self-Adaptive AppearanceBased Eye-Tracking with Online Transfer Learning,” Oct. 2019, doi:https://doi.org/10.1109/bracis.2019.00074.
- 5.] Seonwook Park and Shalini De Mello and Pavlo Molchanov and Umar Iqbal and Otmar Hilliges and Jan Kautz ”Few-Shot Adaptive Gaze Estimation,” ”International Conference on Computer Vision (ICCV)”
- 6.] S. A. Mostafa and I. A. Ahmad, “Recent developments in systematic sampling: A review,” Journal of Statistical Theory and Practice, vol. 12, no. 2, pp. 290–310, Aug. 2017, doi:https://doi.org/10.1080/15598608.2017.1353456.
- 7.] D. E. King, “Dlib-ml: A machine learning toolkit,” Journal of Machine Learning Research, vol. 10, pp. 1755–1758, 2009.
- 8.] J. Deng, W. Dong, R. Socher, L.-J. Li, K. Li, and L. Fei-Fei, “ImageNet: A Large-Scale Hierarchical Image Database,” in CVPR09, 2009.
