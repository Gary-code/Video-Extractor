# Video Features Extractor (2D & 3D Resnet)

> refer [here](https://github.com/thaolmk54/hcrn-videoqa/tree/master/preprocess)

## Requirements and Setup

1. Install Anaconda or Miniconda distribution based on Python3+ from their [downloads' site](https://conda.io/docs/user-guide/install/download.html).
2. Install python package the code needs.

## Pretrain model & Dataset

* Download the off-the-shelf **pre-trained Resent** on Kinetic-400 from the [link](https://drive.google.com/drive/folders/1zvl89AgFAApbH0At-gMuZSeQB_LpNP-M) to extract the motion features of videos.
* **Video datasets** that can be extracted using this code include:
  * [TGIF-QA](https://github.com/YunseokJANG/tgif-qa)
  * [SVQA](https://github.com/SVQA-founder/SVQA)
  * [MSVD-QA & MSRVTT-QA](https://github.com/xudejing/video-question-answering)
  * Extensive Dataset and Customized Dataset

## Extract Video Features

* Apperance Features

```python
python extract_features.py --model resnet101
```

* Motion Features

```python
python extract_features.py --model resnext101
```

