# Chameleon
Chameleon is an efficient continuous adaptation framework based on [NVIDIA TAO](https://developer.nvidia.com/zh-cn/tao-toolkit-get-started). To bridge the gap between one-time domain adaptation and continuous learning, we propose Chameleon, which updates models on new data (labeled or unlabeled) via **existing domain adaptation techniques** and select the suitable model to recovery accuracy through **adaptive model selection methods**. In implementation, we provide different adaptation strategies and optimization techniques for different visual tasks (object detection, segmentation, tracking and SLAM). In the end, we summary existing common optimization techniques (GPU sharing, ...).
## 1. Installation (TAO and Docker)
## 2. Scenarios (adaptation strategies and optimization techniques)
### Object Detection
### Image Segmentation
### Visual Tracking
### SLAM (in progress)
## 3. Common optimization techniques
- GPU Sharing between training and inference: [Ekya: Continuous Learning of Video Analytics Models on Edge Compute Servers. Published in _NSDI'22_.](https://www.microsoft.com/en-us/research/publication/ekya-continuous-learning-of-video-analytics-models-on-edge-compute-servers-2/)
