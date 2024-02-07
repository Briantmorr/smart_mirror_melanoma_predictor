# Smart Mirror for Skin Cancer Detection

## Overview

This project develops a smart mirror designed to detect various types of skin cancer using advanced machine learning models. By leveraging the ISIC 2020 Challenge Dataset, this smart mirror facilitates early detection of skin cancer, highlighting the importance of accessible and non-invasive screening methods.

## Dataset

### ISIC 2020 Challenge Dataset

**Dataset Source:** [ISIC 2020 Challenge Dataset](https://challenge2020.isic-archive.com)

#### About the Dataset

The ISIC 2020 Challenge Dataset contains 33,126 dermoscopic training images from over 2,000 patients, featuring a wide variety of benign and malignant skin lesions. Each image is associated with a unique patient identifier, which has been crucial in tracking the progression of skin lesions over time.

Our analysis revealed that among these 2,000 patients, 997 have images from at least two different visits, indicating the dataset's potential for time-series analysis. This unique aspect allows us to not only identify skin cancer but also observe changes in lesions over time, providing invaluable data for training our model to detect early signs of malignancy.

A significant finding from our exploratory data analysis (EDA) is that, out of the 997 patients with multiple visits, 216 have shown a transition from benign to malignant lesions at the same anatomical site. This subset of the dataset is particularly valuable for training our model to recognize early indicators of malignant transformation in skin lesions.

**DOI:** [https://doi.org/10.34970/2020-ds01](https://doi.org/10.34970/2020-ds01)

[Further reading on Nature](https://www.nature.com/articles/s41597-021-00815-z)

## Model Training

Our model training focuses on convolutional neural networks (CNNs), leveraging the rich variety of the ISIC 2020 dataset. Specifically, we aim to train the model on time-series images to recognize the progression from benign to malignant lesions, an approach that is expected to significantly enhance early detection capabilities.

### Training Goals

The primary goal is to create a model that not only identifies skin cancer but can also track lesion changes over time, making early detection more feasible. This approach is innovative, combining IoT and AI technologies to revolutionize routine skin checks.

## How to Use

- Clone the repository.
- Download and prepare the ISIC 2020 dataset images, focusing on patients with multiple images and especially those showing changes in lesion status.
- Verify you can run the preprocessing_eda notebook

### Citing the Dataset

When utilizing the ISIC 2020 dataset, it's important to attribute it properly as follows:
- International Skin Imaging Collaboration. SIIM-ISIC 2020 Challenge Dataset. International Skin Imaging Collaboration https://doi.org/10.34970/2020-ds01 (2020).
