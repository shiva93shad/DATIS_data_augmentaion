# DATIS: Data Augmentation for Trust Intensity Prediction

## Overview
DATIS (Data Augmentation for Trust Intensity Prediction) is an innovative approach using Generative Adversarial Networks (GANs) to address the challenge of predicting node-level trust intensities in incomplete signed networks. By augmenting data, DATIS effectively enhances the accuracy of regression models tasked with estimating the trustworthiness of nodes in a network.

## Key Features
- **Data Augmentation**: Leverages GANs to generate synthetic data, addressing imbalances in trust intensity values and sign.
- **Regression Model Enhancement**: Improves the performance of regression models by providing a more balanced and comprehensive dataset.
- **Local and Global Feature Utilization**: Uses both local and global network features for a robust prediction model without relying on explicit edge rankings.

## Methodology
### Data Augmentation
- The process begins with feature extraction to prepare input data for the GAN.
- The GAN framework generates new instances of node data, particularly focusing on underrepresented trust intensities.
- These synthetic data points are used to train regression models, improving their ability to predict trust intensities across various nodes.

### Regression Models
- Multiple regression techniques are employed to validate the effectiveness of the augmented data.
- The approach addresses node-level trust prediction as a regression task, providing a nuanced measure of trust based on the augmented data set.

## Getting Started

### Prerequisites
- Python 3.x
- TensorFlow or PyTorch (depending on implementation specifics)
- NumPy, Pandas for data manipulation
- Scikit-learn for regression models
