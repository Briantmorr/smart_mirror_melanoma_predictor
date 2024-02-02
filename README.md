# Smart Mirror for Skin Cancer Detection

## Overview

This project focuses on the development of a smart mirror that can detect various types of skin cancer. Utilizing advanced machine learning models trained on dermatoscopic images, this smart mirror aims to facilitate the early detection of skin cancer.

## Dataset

The model is trained using the HAM10000 dataset, a comprehensive collection of dermatoscopic images of common pigmented skin lesions, available on Kaggle.

**Dataset Source:** [Skin Cancer MNIST: HAM10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000/data)

### About the Dataset

The HAM10000 dataset, or "Human Against Machine with 10000 training images," comprises 10015 dermatoscopic images from various populations, acquired and stored through different modalities. The dataset includes a representative collection of all significant diagnostic categories in the realm of pigmented lesions.

## Model Training

Our model's training process involves using convolutional neural networks (CNNs) to learn from the HAM10000 dataset's diverse set of images. This approach allows the model to accurately identify and classify various skin lesions as benign or malignant.

The following are the seven classes of skin cancer in the dataset:
- Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec)
- Basal cell carcinoma (bcc)
- Benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, bkl)
- Dermatofibroma (df)
- Melanoma (mel)
- Melanocytic nevi (nv)
- Vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, vasc)

These abbreviations are present in the dx column of HAM10000's metadata file.

## Goals and Objectives

The primary objective of this project is to create an innovative solution that leverages IoT and AI technologies for healthcare, specifically in early skin cancer detection. By integrating this technology into an everyday object like a mirror, we aim to make cancer screening more accessible and routine, potentially saving lives through early detection.

## How to Use

- Clone the repository
- Download the 6gb HAM10000 dataset from (Kaggle)[https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000/data]
- unzip and copy the dataset to this repository and rename the folder from archive to data. We are gitignoring the data folder so that it is not uploaded to the repository.
- run preprocessing_eda.py to verify you can successfully load the data

