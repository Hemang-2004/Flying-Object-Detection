# Real-Time Flying Object Detection with YOLOv8

## Overview
This repository demonstrates real-time flying object detection using **YOLOv8**. It includes Jupyter notebooks for custom inference, models trained for generalized (40 classes) and refined (3 classes) use cases, and additional resources such as LaTeX files for the official paper and example videos of model inference.

---

## What's Included
- Jupyter notebook for performing inference on custom source files.
- Two pre-trained models:
  - **Generalized Model**: Trained on 40 classes of flying objects. 
  - **Refined Model**: Focused on detecting 3 specific classes of flying objects.
- LaTeX files for the official research paper.
- Example video demonstrating inference with the generalized model.
- [Source code for the Ultralytics package](https://github.com/ultralytics/ultralytics/tree/main).

---

## Setup and Prerequisites

### 1. Install Dependencies
Ensure you have Python installed. Install the required dependencies with:
```bash
pip install ultralytics torch torchvision
```

## GPU SET UP make sure torch is present
```bash
import torch
torch.cuda.is_available()
torch.cuda.device_count()
```
## Links
- [Ultralytics GitHub](https://github.com/ultralytics/ultralytics/tree/main)
- [YOLOv8 Documentation](https://docs.ultralytics.com/)

