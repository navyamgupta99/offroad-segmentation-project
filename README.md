# Offroad Semantic Segmentation Project

## Task
Semantic segmentation on Offroad dataset.

## Model
U-Net with ResNet34 encoder (ImageNet pretrained)

## Training
- Epochs: 3
- Optimizer: Adam
- Loss: CrossEntropyLoss
- GPU: Tesla T4

## Results
Training loss decreased from:
Epoch 1: 0.6936  
Epoch 2: 0.4158  
Epoch 3: 0.3595  

Model evaluated visually using segmentation outputs.

## Note
Dataset provided is segmentation dataset. mAP50 is not applicable.
