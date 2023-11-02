# Gender Classification in TensorFlow

This repo contains source code implementation of project for NTU CZ4042 Neural Networks and Deep Learning course (2022 Sem1).

## Problem Overview
Automatic gender classification has been used in many applications including image analysis on social 
platforms. The goal of this project is to classify the gender of faces in an image. One can design a 
convolutional neural network to achieve this goal. Some tasks to consider:
1. Modify some previously published architectures e.g., increase the network depth, reducing their 
parameters, etc.
2. Consider age and gender recognition simultaneously to take advantage of the gender-specific age 
characteristics and age-specific gender characteristics inherent to images
3. Consider pre-training using the CelebA dataset 

For training [Adience](https://talhassner.github.io/home/projects/Adience/Adience-data.html#agegender) dataset was used.

## Model Performance

## Submission Files

```
Levi_Hassner_Baseline
│   Levi_hassner.ipynb
│   Levi_hassner-Age.ipynb                                   
|   Levi_hassner-CelebA.ipynb                          // pretrain baseline on CelebA
|   Levi_hassner-depth.ipynb                           // find optimal depth
│  
Classic_CNN_models
|   VGG16-Adience.ipynb										
|   ResNet101-Adience.ipynb								      
|   InceptionV3-Adience.ipynb									
|   EfficientNetB5-Adience.ipynb								 
|   
└───Explore_EfficientNet                              // explore EfficientNet variations 
      ├─ EfficientNetB5-Hyperpara_Tuning.ipynb
      ├─ EfficientNetB5-CelebA.ipynb
      └─ EfficientNetB5-Gender-Age.ipynb              // consider age and gender simultaneously
│
ViT_CLIP                                                      
│   ViT-Adience.ipynb
│   CLIP_Zero-shot-Adience.ipynb
│   
Utils  														
|   Visualize.ipynb

```