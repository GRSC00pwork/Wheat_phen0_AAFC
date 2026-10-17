# **Deep-learning quantification of wheat spike architecture reveals breeding-associated morphotypes and yield determinants**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)


The wheat spike is the primary grain-bearing organ and a key determinant of grain yield, yet, the architectural changes underlying yield gains remain poorly understood, largely because spike phenotyping is labor-intensive and low-throughput. Here, we developed an integrated deep-learning phenotyping pipeline combining semantic and instance segmentation to quantify wheat spike and spikelet architecture from two-dimensional RGB images. Applying this pipeline to 30 Canadian heritage bread wheat cultivars released between 1842 and 2018, we extracted 93 image-derived morphological traits describing spike size, shape, spikelet organization, fertility, and spatial architecture. The semantic and instance segmentation models achieved a mean intersection over union (mIoU) of 0.964 and a mean average precision (mAP50) of 0.92. Image-derived measurements showed strong correlation with manual observations for spike length (r = 0.97), fertile spikelets (r = 0.93), infertile spikelets (r = 0.87), and total spikelets per spike (r = 0.98), validating the accuracy of automated phenotyping. Multivariate analyses identified four distinct spike morphotypes associated with breeding era that differed in grain number, grain yield per spike, and thousand-kernel weight. Temporal analyses revealed a progressive shift toward shorter, more compact spikes with fewer infertile spikelets, larger fertile spikelets, and altered spatial organization, indicating coordinated remodeling of spike architecture during wheat improvement. Structural equation modeling identified spike area, fertile spikelet number, and inter-spikelet spacing as the principal determinants of grain yield through direct and indirect effects. These findings demonstrate that long-term breeding has systematically reshaped wheat spike architecture into distinct yield-associated morphotypes and establish deep-learning phenotyping as a scalable framework for accelerating genetic improvement.

<img width="975" height="772" alt="image" src="https://github.com/user-attachments/assets/66097940-4ff0-4896-bf62-7246e2efdd26" />
Figure 1. Overview of the deep-learning framework and post-processing pipeline for automated wheat spike phenotyping.




## Code availability
All statistical analyses and visualizations were conducted in R software (https://www.r-project.org/) with the RStudio interface using several packages unless otherwise stated (v4.5.2; R Core Team, 2025).

Wheat Spike Phenotyping Configuration and training for RESNET101-U-Net-scse architecture and YOLO11X-seg were developed using Python (v3.10.13; conda-forge) on a a high-performance computing cluster.
