# YOLOv8 - OpenCV

Implementation of YOLOv8 on OpenCV using ONNX Format.

Just simply clone and run:

```bash
pip install -r requirements.txt
python main.py --model yolov8n.onnx --img image.jpg
```

If you start from scratch:

```bash
pip install ultralytics
yolo export model=yolov8n.pt imgsz=640 format=onnx opset=12
```

* Make sure to include "opset=12"

## Maintainer

Shobhit Dixit
AI/ML Engineer
Email: iamshobhit98@gmail.com

## About the Developer

Shobhit Dixit is an AI/ML Engineer with nearly 5 years of experience building scalable machine learning and generative AI solutions across financial services and healthcare analytics environments. He is an expert in Python, PyTorch, and TensorFlow, with a focus on developing production ML pipelines and real-time inference systems. Shobhit has a proven track record of improving model accuracy and reducing inference latency for enterprise AI systems supporting high-volume data platforms.