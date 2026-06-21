# Breast Cancer Detection Using VGG16 and ResNet50V2

## Overview

This project presents a hybrid deep learning approach for breast cancer detection using histopathological breast tissue images. The system leverages the strengths of two powerful Convolutional Neural Networks (CNNs), **VGG16** and **ResNet50V2**, to classify breast cancer images and improve diagnostic accuracy.

The project was developed as part of a research study and has been published in IEEE Xplore.

## Research Publication

**Hybrid Deep Learning-Based Breast Cancer Detection Using VGG16 and ResNet50V2**

📄 IEEE Xplore Publication: https://ieeexplore.ieee.org/document/11465359

## Motivation

Breast cancer is one of the leading causes of cancer-related deaths worldwide. Early and accurate diagnosis plays a crucial role in improving survival rates. Deep learning techniques have demonstrated significant potential in medical image analysis by automatically extracting complex features from histopathological images.

This project aims to:

* Improve breast cancer classification accuracy.
* Compare the performance of VGG16 and ResNet50V2.
* Develop a hybrid deep learning framework for enhanced detection.
* Support medical professionals with AI-assisted diagnosis.

## Dataset

The model is trained using the **BreaKHis (Breast Cancer Histopathological Database)** dataset.

Dataset Characteristics:

* Benign Tumors
* Malignant Tumors
* Multiple magnification levels:

  * 40X
  * 100X
  * 200X
  * 400X

Note: The dataset is not included in this repository due to its large size.

## Methodology

### Data Preprocessing

* Image resizing
* Normalization
* Dataset organization
* Data augmentation

### Deep Learning Models

#### VGG16

* Pre-trained on ImageNet
* Transfer Learning based approach
* Deep feature extraction capability

#### ResNet50V2

* Residual learning architecture
* Improved gradient flow
* Better performance on deep networks

### Hybrid Framework

The proposed system combines the predictive capabilities of VGG16 and ResNet50V2 to achieve robust classification performance.

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

## Project Structure

```text
├── combined_models.ipynb
├── README.md
├── .gitignore
```

## Results

The hybrid model demonstrated strong performance in breast cancer classification by effectively learning discriminative features from histopathological images.

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## How to Run

1. Clone the repository

```bash
git clone https://github.com/Ishita-verma20/Breast-Cancer-Detection-using-VGG16_and-ResNet50v2.git
```

2. Install dependencies

```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn jupyter
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run:

```text
combined_models.ipynb
```

## Future Enhancements

* Explainable AI (XAI) integration
* Attention-based CNN architectures
* Real-time clinical deployment
* Web-based diagnostic dashboard
* Multi-class tumor subtype classification

## Author

**Ishita Verma** ,
**Divyanshu Pathak**

B.Tech – Computer Science Engineering

Researcher | AI & Machine Learning Enthusiast

## Citation

If you use this work in your research, please cite the associated IEEE publication.

