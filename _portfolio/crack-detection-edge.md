---
title: "Intelligent Crack & Corrosion Detection in Infrastructure using Edge Computer Vision"
excerpt: "Deep-learning crack detection running on-board UAVs for real-time infrastructure inspection.<br/><img src='/images/crack_det3.png'>"
collection: portfolio
date: 2022-12-15
---

Building on the autonomous inspection work, this project detects structural cracks directly from aerial imagery using deep learning deployed on edge hardware — enabling real-time assessment during flight rather than offline post-processing.

**Output**
- Reyes-Munoz, J. A., Ortega, A. G., **Rizia, M. M.** (equal contribution), Choudhuri, A., & Flores-Abad, A. *Autonomous aerial system for intelligent close-quarter inspection*, **Int. J. Intelligent Robotics and Applications** (2026, open access). [Article](https://link.springer.com/article/10.1007/s41315-026-00537-8)
- *Deep Learning based Aerial Intelligent Crack Detection in Infrastructure using Computer Vision at the Edge* (preprint, 2022) — [Authorea](https://www.authorea.com/users/566716/articles/613352-intelligent-crack-detection-in-infrastructure-using-computer-vision-at-the-edge)

The system achieved 98.44% mAP@50 for crack detection and 72.33% for corrosion, with onboard AI inference, and was validated in real industrial conditions including a 26 m power-plant stack.

Edge device used: NVIDIA Jetson Nano

![Edge inference hardware: NVIDIA Jetson Nano with Intel RealSense depth and Raspberry Pi RGB cameras.](/images/hardware-handheld.png)

![Real-time surface-crack detection running on the edge device; frame rate shown at the top-left of each frame.](/images/crack_det1.png)

![Corrosion detection across varied lighting and surface conditions.](/images/corrosion-detection-2.png)
