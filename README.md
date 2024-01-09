# Face Recognition System

This repository contains a face recognition system implemented using OpenFace on the CelebA dataset.

## Existing Ideas and References

Explore existing ideas and references related to face recognition:

1. [R-Theta Local Neighborhood Pattern for Unconstrained Facial Image Recognition and Retrieval](https://arxiv.org/pdf/2201.00504v1.pdf)
2. [FaIRCoP: Face Image Retrieval with Attribute Manipulation](https://openaccess.thecvf.com//content/ICCV2021/papers/Zaeemzadeh_Face_Image_Retrieval_With_Attribute_Manipulation_ICCV_2021_paper.pdf)
3. [FaIRCoP: Facial Image Retrieval using Contrastive Personalization](https://arxiv.org/pdf/2205.15870v1.pdf)

## Model Database

### CelebA Dataset

The CelebA dataset is a widely used dataset for face recognition tasks, comprising over 2,000 celebrity images annotated with 40 attribute labels. The dataset is diverse and well-suited for training and evaluating face recognition models.

## Implementation

### Requirements

- [OpenFace](https://github.com/cmusatyalab/openface)
- [dlib](https://pypi.org/project/dlib/) >= 19.3.0
- [numpy](https://pypi.org/project/numpy/)
- [Pillow](https://pypi.org/project/Pillow/)
- [scipy](https://pypi.org/project/scipy/) >= 0.17.0
- [Click](https://pypi.org/project/Click/) >= 6.0
- [face_recognition_models](https://pypi.org/project/face_recognition_models/)
- [CUDA](https://developer.nvidia.com/cuda-downloads) (preferred)

## Results

### Performance Overview

Our face recognition system demonstrates robust performance on the CelebA dataset, achieving a competitive Top-K Accuracy. The model has been evaluated on a diverse set of celebrity images, showcasing its ability to accurately retrieve faces within the top-K results.

### Quantitative Results

The Top-K Accuracy of the face recognition system is consistently high, reaching 84% on average(max: 98%, min: 67%). This metric reflects the system's efficiency in correctly identifying relevant faces within the specified retrieval range.

### Qualitative Results

In addition to quantitative metrics, qualitative analysis reveals the model's capability to recognize faces across various attributes, lighting conditions, and facial expressions. The system excels in capturing subtle features, contributing to its overall robustness.

### Failure Cases

While our model generally performs well, there are certain challenging scenarios where it may encounter difficulties. Some identified failure cases include:

1. **Very Low Lighting Conditions:** The model may struggle with faces captured in extremely very low-light environments, affecting its ability to extract accurate facial features.

2. **Partial Occlusion:** Instances where a significant portion of the face is occluded, such as by sunglasses or hair or a mask, may result in reduced recognition accuracy.

3. **Similar Looking Faces:** In cases where individuals share similar facial features, the model may face challenges in distinguishing between them.

A proper model assessment couldn't be done due to lack on time on my side.
