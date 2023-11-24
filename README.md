# 2023 NTU ADL Final Project - Group 8
## Environment
* Linux (Ubuntu)
* Python >= 3.6 (Pytorch)
* NVIDIA GPU + CUDA CuDNN
```
  cd 23-ADL-Final-Project
  pip install -r requirements.txt
```

## Download
Use gdown to download dataset from Google Drive:
```
  bash download.sh
```

## Preprocess
```
  python preprocess/image_to_256.py
```
```
  python preprocess/image_to_512.py
```
