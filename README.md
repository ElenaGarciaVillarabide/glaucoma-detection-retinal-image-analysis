# Automatic Glaucoma Detection through Retinal Image Analysis

## Overview
This project focuses on glaucoma support detection from retinal fundus images through deep learning-based segmentation of the optic disc and optic cup. The main objective was to estimate the cup-to-disc ratio (CDR), an important clinical indicator used in glaucoma assessment, and use it to support automatic glaucoma suspicion detection.

The project was developed as a team academic project and included image preprocessing, model training and evaluation, comparison of segmentation architectures, and the development of an interactive interface for image upload and result visualization.

## Objectives
- Develop a retinal image analysis workflow for glaucoma support detection
- Segment the optic disc and optic cup from fundus images
- Estimate the cup-to-disc ratio (CDR) automatically
- Compare deep learning architectures for semantic segmentation
- Build an interface for image upload and prediction

## Project Workflow
- Image preprocessing
- Optic disc and optic cup segmentation
- Model training and validation
- Architecture comparison
- CDR estimation from predicted masks
- Automatic glaucoma suspicion output

## Models Explored
- U-Net with ResNet34
- DeepLabv3+ with ResNet50

## Selected Model
The model selected for the final implementation was **U-Net with ResNet34**, based on its performance in optic disc and optic cup segmentation.

## Interface
A simple interface was developed using **Gradio**, allowing the user to:
- upload a retinal fundus image
- obtain the predicted segmentation
- view the estimated optic disc and optic cup measurements
- calculate the cup-to-disc ratio (CDR)
- receive an automatic glaucoma suspicion result

In the implemented logic, **CDR values above 0.6** were considered suspicious for glaucoma.

## Technologies
- Python
- PyTorch
- Gradio
- Deep Learning
- Computer Vision
- Medical Image Analysis

## Main Features
- Retinal image preprocessing
- Optic disc and optic cup segmentation
- CDR calculation
- Automatic glaucoma suspicion output
- Interactive interface for prediction

## Team Project
This project was developed as a team academic project.

## My Contribution
I contributed to the development of the retinal image analysis workflow, including model-related work, evaluation tasks, and support in the implementation of the interactive prediction interface.

## Learning Outcomes
Through this project, I strengthened my skills in:
- biomedical image analysis
- semantic segmentation
- deep learning model comparison
- clinical metric estimation from images
- deployment of simple machine learning interfaces

## Notes
This repository includes the source code and supporting materials related to the project. The dataset may not be included in the repository if it is subject to usage restrictions.

## Author
Elena García Villarabide
