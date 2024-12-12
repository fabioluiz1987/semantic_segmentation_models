# Semantic Segmentation Models

This repository contains the trained models used in the article titled **"Cooperation between Ground and Aerial Robotic Platforms for Target Detection and Tracking using Deep Learning"**. The models were trained for semantic segmentation tasks, specifically aimed at identifying traversable and non-traversable areas in aerial images. These models can be used to generate navigability maps for ground robots (UGVs).

## Overview

The following pre-trained models are provided:

- **MobileNet V2**
- **ResNet 50**
- **ResNet 101**
- **EfficientNet-B4**
- **EfficientNet-B5**

Each model was trained using the [Semantic Drone Dataset](http://dronedataset.icg.tugraz.at/) and evaluated for its accuracy, mean Intersection over Union (mIoU), and inference time. The detailed performance metrics can be found in the corresponding article.
