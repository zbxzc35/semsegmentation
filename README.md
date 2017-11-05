# Semantic Segmentation
This repository contains implementations of popular semantic segmentation algorithms implemented in PyTorch

## Models
1. Vanilla FCN: FCN32, FCN16, FCN8, in the versions of VGG, ResNet and DenseNet respectively
([Fully convolutional networks for semantic segmentation](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Long_Fully_Convolutional_Networks_2015_CVPR_paper.pdf))
2. U-Net ([U-net: Convolutional networks for biomedical image segmentation](https://arxiv.org/pdf/1505.04597))
3. SegNet ([Segnet: A deep convolutional encoder-decoder architecture for image segmentation](https://arxiv.org/pdf/1511.00561))
4. Tiramisu Dense-Net ([The One Hundred Layers Tiramisu: Fully Convolutional DenseNets for Semantic Segmentation]) (https://arxiv.org/pdf/1611.09326.pdf)


## Requirement
1. PyTorch 0.2.0


## Preparation
1. Go to *models* directory and set the path of pretrained models in *config.py*
2. Go to *datasets* directory and do according to procedure in the README

## TODO
1. Tiramisu (DenseNet) 
