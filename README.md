# Entropy-Guided Weighted Adversarial Open-Set Domain Adaptation Method for Hyperspectral Image Classification
This is a code demo for the paper "Entropy-Guided Weighted Adversarial Open-Set Domain Adaptation Method for Hyperspectral Image Classification"


## Requirements
- Python Version: 3.8.20

- TorchMetrics Version: 1.5.1

- PyTorch Version: 1.12.0+cu113

- Scikit-learn Version: 1.3.2

- SciPy Version: 1.10.1


## Datasets
Download dataset from the following link (code is `qwer`):[BaiduYun](https://pan.baidu.com/s/1di_HKhPfGGXn_Ul8r35Lfg), and move the files to folder`./datasets` .

An example datasets folder has the following structure:
```
datasets

├── PU-PC
│   ├── paviaU_gt_7.mat(source dataset)
│   ├── PaviaC_OS_gt.npy(target dataset)
├── HU13-HU18
│   ├── Houston13_7gt.mat(source dataset)
│   └── Houston18_7gt.mat(target dataset)
```

## Usage
The pipeline for training with EGWA_OSDA is the following (The code is still being optimized):
1. Download the required dataset and move to folder`./datasets`.
2. run the script `train.py`
