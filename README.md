# Dataset Conversion Scripts

This repository contains Python scripts designed to convert some popular datasets into the YOLO v10 format. The datasets currently supported are "A Diverse Driving Dataset for Heterogeneous Multitask Learning. datasets(__BDD100K__)", "German Traffic Sign Recognition Benchmark (__GTSRB__)", and "Tsinghua-Tencent 100k (__TT100K__)". Each script handles the specific preprocessing and annotation conversion required for these datasets, facilitating their use in training YOLO-based object detection models.

## Contents

1. **BDD100K to YOLO v10 Converter (`Convert BDD100k to YOLOv10.ipynb`)**
   - This script converts the BDD100K dataset annotations into the YOLO v10 format. The BDD100K dataset includes a wide range of images with diverse driving scenarios. The script handles the extraction and transformation of bounding box annotations to match YOLO v10 requirements and also can be used to isolate a specific class based on the need.

2. **GTSRB to YOLO Converter (`Convert GTRSB to Yolov10.ipynb`)**
   - The GTSRB (German Traffic Sign Recognition Benchmark) dataset is a popular dataset for traffic sign recognition tasks. This script converts the GTSRB dataset annotations into YOLO-compatible format, making it easier to train YOLO models for traffic sign detection.

3. **TT100K to YOLO v10 Converter (`Convert TTK100K to YOLOv10.ipynb`)**
   - This script converts the TT100K dataset, which consists of Chinese traffic signs, into the YOLO v10 format. It processes the dataset's annotations and ensures compatibility with the YOLO v10 framework, supporting efficient training and evaluation.


## Acknowledgments

- **BDD100K Dataset**: Berkeley DeepDrive
- **GTSRB Dataset**: German Traffic Sign Recognition Benchmark
- **TT100K Dataset**: Tencent

---

Feel free to customize this README further based on specific details or instructions you want to include.
