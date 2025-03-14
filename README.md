# Top-View Vehicle Detection in Noisy Urban Environments 
This project focuses on top-view vehicle detection using image processing and segmentation techniques to identify and track vehicles in noisy urban environments accurately. The system is designed to enhance traffic monitoring, autonomous driving, and smart city applications by leveraging advanced computer vision algorithms.

# Project Overview -
Vehicle detection from a top-down perspective is crucial for analyzing traffic flow, congestion management, and urban planning. Unlike traditional side-view detection, top-view analysis provides a clearer understanding of vehicle movement, density, and parking patterns. However, occlusions, noise, and varying lighting conditions challenge achieving accurate segmentation.

This project addresses these challenges by developing a robust image processing pipeline that integrates noise reduction, multi-level segmentation, and region-based processing techniques. The system evaluates different filtering and segmentation methods to identify the most effective approach for vehicle detection in complex urban environments.

# Key Features -
✔ Advanced Noise Reduction – Utilizes Gaussian, Median, Wiener, and Bilateral Filters to enhance image clarity and reduce artifacts.

✔ Multi-Level Segmentation – Implements K-Means, Mean Shift, and Graph-Based Segmentation for extracting vehicle regions.

✔ Region-Based Processing – Uses Region-Growing and Connected Component Analysis (CCA) to refine detections and remove noise.

✔ Performance Evaluation – Assesses segmentation accuracy using Intersection over Union (IoU), Dice Coefficient, and Pixel Accuracy.

# Technologies Used -
Programming Language: Python

Algorithms: K-Means, Mean Shift, Graph-Based Segmentation, Wiener Filter, Region-Growing, Connected Component Analysis

Evaluation Metrics: IoU, Dice Coefficient, Pixel Accuracy
