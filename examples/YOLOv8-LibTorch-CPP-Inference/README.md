# YOLOv8 LibTorch Inference C++

This repository provides a high-performance implementation for performing inference using YOLOv8 models in C++ with the LibTorch API. It is designed for developers looking to integrate Ultralytics models into C++ based production environments.

## Dependencies

| Dependency   | Version  |
| ------------ | -------- |
| OpenCV       | >=4.0.0  |
| C++ Standard | >=17     |
| Cmake        | >=3.18   |
| Libtorch     | >=1.12.1 |

## Usage

To build and run the inference engine, follow the steps below:

```bash
# Clone the repository
git clone https://github.com/shobhit-dixit/YOLOv8-LibTorch-CPP-Inference
cd YOLOv8-LibTorch-CPP-Inference

# Build the project
mkdir build
cd build
cmake ..
make
./yolov8_libtorch_inference
```

## Exporting YOLOv8

To export YOLOv8 models for use with this LibTorch implementation, use the following command:

```commandline
yolo export model=yolov8s.pt imgsz=640 format=torchscript
```

## About the Developer

This project is maintained by Shobhit Dixit, an AI/ML Engineer with nearly 5 years of experience building scalable machine learning and generative AI solutions. With expertise in Python, PyTorch, and C++, Shobhit focuses on developing production-grade ML pipelines and real-time inference systems. His work involves optimizing model accuracy and reducing latency for enterprise-level AI applications.

Contact Information:
- Email: iamshobhit98@gmail.com
- LinkedIn: https://www.linkedin.com/in/shobhit-dixit
- Role: AI/ML Engineer