
# FeatureNet classification Replication in Pytorch

This repository provides a PyTorch implementation of FeatureNet, a 3D shape classification model using voxelized data. The goal is to replicate the architecture and approach from the paper "FeatureNet: A Feature Convolutional Neural Network for 3D Shape Classification". The model is designed to classify 3D shapes by extracting meaningful features from voxelized representations, enabling effective shape recognition in applications such as manufacturing feature recognition method.


- For more details, refer to the original paper: [FeatureNet: Machining feature recognition based on 3D Convolution Neural Network.](https://www.sciencedirect.com/science/article/pii/S0010448518301349)
- The FeatureNet implementaion in tensorflow can be found at: [FeatureNet](https://gitlab.com/qub_femg/machine-learning/featurenet-tensorflow-2) 
- To see its comparison to sparse voxel-based method for manufacturing feature recognition go to:   [Manufacturing Feature Recognition with a Sparse Voxel-based Convolutional Neural Network](https://asmedigitalcollection.asme.org/computingengineering/article/25/3/031002/1210226)
- The binvox-rw.py library used in this code is borrowed from this library: [binvox_rw](https://github.com/dimatura/binvox-rw-py)


## Dataset:
The dataset used for this project can be found here M[achining-feature-dataset](https://github.com/madlabub/Machining-feature-dataset). Keep in mind that the folder stucture of the original datastructure is different from what was used in this project.


## Dependencies:
The dependencies can be found in pyproject.toml


## Contact:
If you have any question email me at vatandoustf@gmail.com send me massage on [linkedin](https://www.linkedin.com/in/farzad-vatandoust/).
My version of the dataset can be provided upon request.







