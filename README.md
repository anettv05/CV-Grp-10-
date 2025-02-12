# Plant Disease Detection: RGB and Thermal Imaging

## Dataset Information
- **RGB Dataset**: https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color
- **Thermal Dataset**: https://www.kaggle.com/datasets/sujaradha/thermal-images-diseased-healthy-leaves-paddy

## Implemented Deep Learning Models

### Semantic Segmentation Models
- UNet
- SegNet

### Classification Models
- ResNet
- GoogleNet
- VGG
- AlexNet
- Inception V3
- EfficientNetV2
- Vision Transformer (ViT)

### Object Detection Models
- R-CNN
- YOLOv11

## Model Performance Comparison

### RGB Dataset Accuracies

| Model           | Accuracy (%) |
|----------------|--------------|
| UNet           | -   97.00    |
| ResNet         | -   99.19    |
| SegNet         | -   99.59    |
| GoogleNet      | -   99.67    |
| VGG 16         | -   99.54    |
| AlexNet        | -   98.67    |
| Inception V3   | -   91.43    |
| R-CNN          | -   42.33    |
| YOLOv11        | -   98.00    |
| ViT            | -   91.70    |
| EfficientNetV2 | -   99.30    |

### Thermal Dataset Accuracies

| Model           | Accuracy (%) |
|----------------|--------------|
| UNet           | -   54.00    |
| ResNet         | -   94.50    |
| SegNet         | -   91.29    |
| GoogleNet      | -   93.18    |
| VGG 16         | -   98.96    |
| AlexNet        | -   99.48    |
| Inception V3   | -   98.69    |
| R-CNN          | -   35.33    |
| YOLOv11        | -   73.40    |
| ViT            | -   62.20    |
| EfficientNetV2 | -   94.40    |

## Best Performing Models
- RGB Dataset: [GoogleNet]
- Thermal Dataset: [AlexNet]
