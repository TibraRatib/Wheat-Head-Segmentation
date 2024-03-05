# Wheat-Head-Segmentation

## Overview
This project aims to address the primary issue of developing advanced wheat head segmentation models capable of navigating the complexities posed by diverse growing conditions. Visual challenges such as overlapping plants, variations in appearance due to maturity, genotype, and the impact of environmental factors like wind-induced blurring make accurate wheat head segmentation difficult.


## Dataset:
The dataset for this project from Global Wheat Detection  we taken photos of Wheat  and then uploading them to the CVAT platform. 

The dataset used for this project is sourced from the Global Wheat Detection [data](https://www.kaggle.com/competitions/global-wheat-detection ). Images of wheat were  uploaded to the CVAT platform for annotation and labeling. This dataset serves as the foundation for training and evaluating wheat head segmentation models [dataset](https://www.kaggle.com/datasets/batoolsmadi/wheat-head-segmentation-data).

### Data Annotation:
CVAT was used for annotation, making the dataset ready for training the segmentation models (YOLOv8 , SAM , UNet).

Example Annotated Images:

<div style="display: flex; flex-direction: column; justify-content: space-between;">
  <img src="examples/annotated/1.png" alt="Example Annotated Image 1" width="300"/>
  <img src="examples/annotated/2.png" alt="Example Annotated Image 2" width="300"/>
</div>

## Methodology
The project utilizes three distinct architectures for wheat head segmentation:

### SAM (Segment Anything Model):
SAM is a versatile segmentation architecture capable of accurately delineating objects of interest across diverse environments. It employs a spatial attention mechanism to focus on relevant regions, enabling precise segmentation even in challenging scenarios such as overlapping plants and varying appearance due to environmental factors.
### YOLOv8: 
YOLOv8, an iteration of the You Only Look Once (YOLO) object detection model, is adapted for wheat head segmentation. Its real-time processing capabilities and efficient architecture make it well-suited for this task, especially in scenarios where speed is crucial.
### UNet:
UNet, a convolutional neural network architecture designed for biomedical image segmentation, is employed for its ability to capture intricate features and spatial relationships within wheat head images. It excels in scenarios where precise delineation of objects is essential.


