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

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/face-recognition-system.git

# Navigate to the project directory
cd face-reco

# Install dependencies
pip install -r requirements.txt
