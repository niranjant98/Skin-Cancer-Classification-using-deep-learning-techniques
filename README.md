

## Overview
This project leverages deep learning techniques to classify skin cancer lesions accurately. Utilizing state-of-the-art models and methods, we aim to contribute to early detection efforts that are vital for patient care.

## 🧠 Project Highlights
- **Custom CNN**: Built from scratch for a baseline classification task.
- **Transfer Learning**: Incorporates pre-trained architectures:
  - **ResNet50**: A deep residual network for efficient feature extraction.
  - **VGG16**: A proven model for robust image classification tasks.

## 📊 Dataset
We used the **HAM10000** dataset, containing 10,015 dermoscopic images of seven lesion types. Key preprocessing techniques include:
- **Normalization** for consistent input.
- **Class balancing** to address imbalanced data.

## 🚀 Features
- **End-to-End Workflow**: Includes preprocessing, model training, evaluation, and visualization.
- **Transfer Learning**: Comparative analysis of different models on identical tasks.
- **Evaluation Metrics**: Tracks accuracy, precision, recall, and F1-score.


## 📜 Reference
> H. L. Gururaj, N. Manju, A. Nagarjun, V. N. Manjunath Aradhya, and F. Flammini,  
> "DeepSkin: A Deep Learning Approach for Skin Cancer Classification,"  
> *IEEE Access*, vol. 11, pp. 50205–50214, May 2023, doi: [10.1109/ACCESS.2023.3274848](https://doi.org/10.1109/ACCESS.2023.3274848).

## 🛠️ Future Enhancements
- **Data Augmentation**: Improve model generalization and address overfitting.
- **Integration of DenseNet**: Evaluate its performance against existing models.
- **Real-time Deployment**: Create a web interface for real-time lesion classification.
- **Explainability Tools**: Add visualization tools to interpret model predictions better.

