# Depth Map Generation for FASD Data Set

This is an adption of python PRN implementation. 



## Getting Started

1. Download the PRN trained model at [BaiduDrive](https://pan.baidu.com/s/10vuV7m00OHLcsihaC-Adsw) or [GoogleDrive](https://drive.google.com/file/d/1UoE-XuW1SDLUjZmJPkIZ1MLxvQFgmTFH/view?usp=sharing), and put it into `Data/net-data`

2. Download FASD data set at [HessenBox](https://hessenbox.tu-darmstadt.de/getlink/fiTgGfkGrAcY9tbA6PmdFbf2/casia-fasd-frames-only.zip) and copy its content in ../

- $ conda env create -f environment.yml

For test_release frames: 

- $ python generate.py --isTest=True

For train_release frames: 

- $ python generate.py --isTest=False

## Source

[PRNet](https://github.com/YadiraF/PRNet/)

```
@inProceedings{feng2018prn,
  title     = {Joint 3D Face Reconstruction and Dense Alignment with Position Map Regression Network},
  author    = {Yao Feng and Fan Wu and Xiaohu Shao and Yanfeng Wang and Xi Zhou},
  booktitle = {ECCV},
  year      = {2018}
}
```


