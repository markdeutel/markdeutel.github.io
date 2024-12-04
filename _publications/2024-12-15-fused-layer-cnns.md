---
title: "Fused-Layer CNNs for Memory-Efficient Inference on Microcontrollers"
collection: publications
category: conferences
permalink: /publication/fusedLayerCnns
excerpt: 'Convolutional Neural Networks (CNNs) have been established as the dominant approach to computer vision tasks. As a result, efficient inference of CNNs has become a major concern to enable the processing of image data close to where it is generated by camera sensors, most commonly microcontroller units (MCUs). However, major obstacles to deploying CNNs on MCUs are the strict memory and bandwidth constraints that make processing high-resolution images on many MCUs infeasible. In this work, we propose a method to fuse convolutional layers in quantized CNNs, which can serve as an additional dimension for optimizing the memory requirements of CNNs during inference. By fusing memory-intensive convolutions in the early inverted residual blocks of MobileNetv2-like CNNs, we show that memory requirements during inference can be reduced by up to 54% at the cost of only about a 14% increase in latency and no change in accuracy. As an example, we show that this reduction enables the deployment of image processing pipelines on a Cortex-M7 MCU that supports image resolutions up to 320x320 pixels compared to the 128x128 pixels resolution commonly used in related work.'
date: 2024-12-15
venue: 'Workshop on Machine Learning and Compression @ NeurIPS 2024'
paperurl: 'https://openreview.net/forum?id=2O8qbyxH6X'
highlight: '../files/fused_layer_cnn_highlight.png'
citation: 'Deutel, M., Hannig F., Mutschler, C., & Teich, J. (2024). Fused-Layer CNNs for Memory-Efficient Inference on Microcontrollers. In Workshop on Machine Learning and Compression @ NeurIPS 2024.'
---

This work-in-progress paper presents results on the feasibility of single-shot object detection on microcontrollers using YOLO. Single-shot object detectors like YOLO are widely used, however due to their complexity mainly on larger GPU-based platforms. We present microYOLO, which can be used on Cortex-M based microcontrollers, such as the OpenMV H7 R2, achieving about 3.5 FPS when classifying 128x128 RGB images while using less than 800 KB Flash and less than 350 KB RAM. Furthermore, we share experimental results for three different object detection tasks, analyzing the accuracy of microYOLO on them.