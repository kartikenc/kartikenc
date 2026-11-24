# Kartik E. Cholachgudda

**Assistant Professor, Robotics & Artificial Intelligence, School of ECE, REVA University, Bengaluru**  
Lead, RECA Labs (Robotics · Embedded Systems · Computer Vision · AI) · Tech Guru, REVA-AICTE IDEA Lab

I take perception and state-estimation algorithms from the whiteboard to flight-tested, field-tested hardware, and I publish the code, data and flight logs so anyone can check the numbers.

[LinkedIn](https://www.linkedin.com/in/kartik-cholachgudda-0b407239/) · [Google Scholar](https://scholar.google.co.in/citations?user=xyhbIJ0AAAAJ) · [ORCID](https://orcid.org/0000-0002-9217-6884) · [Scopus](https://www.scopus.com/authid/detail.uri?authorId=57217103323) · [Vidwan](https://vidwan.inflibnet.ac.in/profile/334009) · kartik.c@reva.edu.in

---

### Now

- **UAV autonomy:** following up the VQA-EKF flight study (submitted) with in-flight RGB/IR camera switching, and building the SANJEEVANI search-and-rescue drone for Smart India Hackathon 2026
- **Crop-disease sensing (PhD):** AgRECA field campaign and multi-source fusion for grapevine downy mildew severity
- **Autonomous ground vehicles:** REVA L2 autonomous campus buggy, and the ROS 2 AMR fleet in the Autonomous Robot Systems lab

### Flagship work

| Repository | What it is | Headline result |
|---|---|---|
| [vqa-ekf-ardupilot-landing](https://github.com/kartikenc/vqa-ekf-ardupilot-landing) | Per-fix vision noise σ²(θ, L) from tilt and image sharpness, fed to the unmodified ArduPilot EKF3 for marker-based landing | Vision-only touchdowns 47% less dispersed than a constant-noise baseline (p = 0.034), 90 randomised sorties |
| [grapevine-downy-mildew-classification](https://github.com/kartikenc/grapevine-downy-mildew-classification) | 16-model benchmark (5 classical, 11 deep) for five-class severity from field images, with edge deployment | ViT-S/16 87.8% accuracy; MobileNetV2 at 22.45 FPS on a Raspberry Pi 5 |
| [grapevine-downy-mildew-severity](https://github.com/kartikenc/grapevine-downy-mildew-severity) | Two-stage pipeline: U-Net (ResNet-34) leaf segmentation + Random Forest on 75 interpretable features | Dice 0.992; quadratic-weighted κ 0.922 |
| [amr-ros2-jetson](https://github.com/kartikenc/amr-ros2-jetson) | ROS 2 autonomous mobile robot stack on Jetson Nano: LiDAR SLAM, fused odometry, navigation, fleet diagnostics | Validated on a fleet of ten identical teaching robots |
| [idealab](https://github.com/kartikenc/idealab) | QR-linked reference pages for the REVA-AICTE IDEA Lab wall boards | [Live site](https://kartikenc.github.io/idealab/) |

### Record

- **8 Scopus-indexed publications** (IEEE CONECCT, APSCON, TENSYMP, R10-HTC, ICoAC; ACM IC3; CRC Press chapter); Google Scholar: 37 citations, h-index 4
- **Patents:** Australian Innovation Patent 2021102047 (granted 2021), contactless user identification and temperature detection; Indian application 202041044283
- **Funded work:** VGST (Govt. of Karnataka) GRD 954, high-throughput phenotyping for grape vineyards; REVA seed grants; winner, AIC-PECF COVID Innovation Challenge
- **Open data:** grapevine downy mildew field dataset, 920 images, [doi:10.5281/zenodo.20701851](https://doi.org/10.5281/zenodo.20701851)
- **Service:** Recognised Reviewer, *Computers and Electronics in Agriculture* (Elsevier); reviewer, *Information Processing in Agriculture*

### Selected publications

- K. E. Cholachgudda et al., "System Architecture and Software Design of a Handheld High Throughput Phenotyping Device: AgRECA," IEEE APSCON, 2023. [doi](https://doi.org/10.1109/APSCON56343.2023.10101056)
- S. Mandal, K. E. Cholachgudda et al., "JetVision: A Low-Cost Real-Time Depth Estimation System using Jetson Computing Platform," IEEE CONECCT, 2023. [doi](https://doi.org/10.1109/CONECCT57959.2023.10234820)
- K. E. Cholachgudda et al., "Design of a Multispectral and Thermal Data Acquisition System for High-Throughput Phenotyping of Plant Pathology," IEEE CONECCT, 2022. [doi](https://doi.org/10.1109/CONECCT55679.2022.9865773)
- K. E. Cholachgudda et al., "Performance Analysis of Deep Neural Networks for Tomato Leaf Disease Classification with Server-Based Computing," IEEE R10-HTC, 2021. [doi](https://doi.org/10.1109/R10-HTC53172.2021.9641733)
- K. E. Cholachgudda, R. C. Biradar, M. Lokanath, "Geometric Calibration of a Time-of-Flight Depth Sensor and a Colour Camera Pair," ICoAC, 2019. [doi](https://doi.org/10.1109/ICoAC48765.2019.246859)

Full list: [Google Scholar](https://scholar.google.co.in/citations?user=xyhbIJ0AAAAJ)

### Teaching

Robot Operating System (ROS 2 Jazzy, Gazebo Harmonic) · Autonomous Robot Systems · Machine Learning for Robotics (Bayes, Kalman and particle filters, Q-learning) · Python Programming and Applications · FDPs on UAVs and agricultural robotics

### Built with

Python · C++ · ROS 2 · ArduPilot / MAVLink · PyTorch · OpenCV · ONNX Runtime · CUDA · Raspberry Pi 5 · NVIDIA Jetson · OAK-D · ESP32 · KiCad

### Work with me

Research collaboration (UAV autonomy, agri-sensing, edge AI), sponsored student projects, consultancy through REVA University, and training programmes. Students: email me with the subject line `Project: <topic>`, a few lines on what you have built, and a link to your code.
