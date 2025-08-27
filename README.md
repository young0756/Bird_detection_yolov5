# Bird_detection_yolov5
This repository leverages YOLOv5 to perform fast and real-time bird detection. It utilizes a pre-trained YOLOv5s model to achieve efficient and accurate inference.

## Quick Start
```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2.Run inference
python detect.py --weights best.pt --source 0 --nosave --exist-ok
```

## Requirements

### Hardware Recommendations
- **GPU**: NVIDA RTX 3070 or better
- **RAM**: 32GB+
- **CPU**: Modern multi-core processor

### Software Requirements
- **OS**: Windows 11
- **Python**: 3.8
- **CUDA**: 11.8+ or 12.0+
