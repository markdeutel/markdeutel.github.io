---
title: "Unsupervised Learning of Variational Autoencoders on Cortex-M Microcontrollers"
collection: publications
category: conferences
permalink: /publication/unsuper-learn-vaes-mcus
excerpt: "Training and fine-tuning deep neural networks (DNNs) to adapt to new and unseen data at the edge has recently attracted considerable research interest. However, most work to date has focused on supervised learning of pre-trained, quantized DNNs. Although these proposed techniques are advantageous in enabling DNN training even on resource-constrained devices such as microcontroller units (MCUs), they do not address the issue that large amounts of labeled data are required to perform supervised training. Moreover, while data are readily available at the edge, ground-truth labels are typically not. In this work, we explore variational autoencoders as a way to train unsupervised, i.e., without labels, feature extractors for image classification on a Cortex-M MCU. Using these feature extractors, we then train classification heads using small labeled representative sets of data to solve classification tasks. Our approach significantly reduces the amount of labeled data required, while enabling full DNN training from scratch on resource-constrained devices."
date: 2025-12-31
venue: 'IEEE 18th International Symposium on Embedded Multicore/Many-core Systems-on-Chip (MCSoC)'
paperurl: 'https://doi.org/10.1109/MCSoC67473.2025.00079'
openurl: '../files/MCSoC25_VAEs_on_Microcontrollers_camera_ready.pdf'
slidesurl: '../files/MCSoC_Unuspervised_On_Device_Deutel.pdf'
highlight: '../files/unsupervised_on_device_overview.png	'
citation: 'Deutel, M., Plinge, A., Seuß, D., Mutschler, C., Hannig, F., & Teich, J. (2025). Unsupervised Learning of Variational Autoencoders on Cortex-M Microcontrollers. IEEE 18th International Symposium on Embedded Multicore/Many-core Systems-on-Chip (MCSoC).'
---

Training and fine-tuning deep neural networks (DNNs) to adapt to new and unseen data at the edge has recently attracted considerable research interest. However, most work to date has focused on supervised learning of pre-trained, quantized DNNs. Although these proposed techniques are advantageous in enabling DNN training even on resource-constrained devices such as microcontroller units (MCUs), they do not address the issue that large amounts of labeled data are required to perform supervised training. Moreover, while data are readily available at the edge, ground-truth labels are typically not. In this work, we explore variational autoencoders as a way to train unsupervised, i.e., without labels, feature extractors for image classification on a Cortex-M MCU. Using these feature extractors, we then train classification heads using small labeled representative sets of data to solve classification tasks. Our approach significantly reduces the amount of labeled data required, while enabling full DNN training from scratch on resource-constrained devices.