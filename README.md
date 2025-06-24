# Video Attention Classification

## Overview
Video-based attention classification model training and evaluation code.

## Structure
```
video-attention-classification/
├── configs/           # Configuration files
├── data/              # Dataset
├── evaluation/        # Evaluation scripts
├── losses/            # Custom loss functions
├── models/            # Model definitions
├── utils/             # Utility functions
├── main.py            # Training/Evaluation entry point
├── inference.py       # Inference script
├── README.md
├── requirements.txt
```

## Quick Start

### 1. Install requirements
```bash
pip install -r requirements.txt
```

### 2. Train
```bash
python main.py --config configs/default.yaml
```

### 3. Inference
```bash
python inference.py --model_path outputs/best_model.pth --input data/test.mp4
```

## Requirements
- torch
- torchvision
- opencv-python
- numpy
- pandas
- pyyaml

(See requirements.txt for details)
