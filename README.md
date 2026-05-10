<div align="center">
  
# 🧠 Pattern Recognition & Machine Learning Lab 

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

*A comprehensive collection of machine learning, computer vision, and pattern recognition experiments.*

</div>

---

## 📖 Overview

This repository contains a curated series of structured laboratory experiments exploring core concepts in **Machine Learning**, **Computer Vision**, and **Pattern Recognition**. The experiments progress from fundamental statistical modeling and regression to advanced deep learning architectures for semantic segmentation and biological data analysis.

---

## 🔬 Experiments Portfolio

| Exp. | Topic | Description | Status |
| :---: | :--- | :--- | :---: |
| **01** | **Environment Setup & Linear Regression** | Installing Anaconda, setting up the environment, installing supporting packages, and implementing basic Linear Regression. | ✅ |
| **02** | **Curve Fitting & Error Metrics** | Linear and Non-Linear Regression, curve fitting for regression problems, error correction methods, MSE, and MAE. | ✅ |
| **03** | **Logistic Regression & Classification Metrics** | Sigmoid function for classification. Analysis of TPR, FPR, TNR, FNR, Recall, Precision, Sensitivity, and ROC-AUC curves. | ✅ |
| **04** | **Unsupervised Learning & Clustering** | Implementation of k-Means Clustering algorithm and determining optimal clusters using the Elbow Rule. | ✅ |
| **05** | **Classical Image Segmentation** | Exploring traditional vision techniques like thresholding, region-based segmentation, and edge-based segmentation to partition images into meaningful regions. | ✅ |
| **06** | **Semantic Segmentation (Deep Learning)** | Advanced pixel-wise Semantic Segmentation using customized deep learning models. | ✅ |
| **07** | **Instance Segmentation** | Deep learning models applied to Instance Segmentation, distinguishing between different objects of the same class. | ✅ |
| **08** | **CNN Image Classification** | Building a Convolutional Neural Network (CNN) architecture from scratch for multi-class image classification on benchmark datasets (like CIFAR-10 or MNIST). | ✅ |
| **09 & 10** | **Isolation Forest on Biological Data** | Using Isolation Forest to analyze and identify anomalies/patterns in biological data. Applications include analyzing DNA/RNA sequences and nuclei patterns to uncover new biomarkers and study evolutionary cell expression data. | ✅ |
| **11** | **Pattern & Movement Recognition** | Developing Neural Networks for advanced Pattern and Hand Movement Recognition. | ✅ |

---

## 📂 Repository Structure

The codebase is organized modularly by experiment topic for easy navigation:

```text
📁 Repository Root
│
├── 📂 Linear/                                  # Experiments 1-3: Regression & Classification 
├── 📂 K-Means/                                 # Experiment 4: Unsupervised Learning
├── 📂 Image_Segmentation/                      # Experiment 5: Classical Segmentation
├── 📂 U-Net_From_Scratch/                      # Experiment 6: Semantic Segmentation
├── 📂 Instance segmentation/                   # Experiment 7: Instance Segmentation
├── 📂 CNN Image Classification/                # Experiment 8: CNN Architecture
├── 📂 Isolation_Forest_Biological_data/        # Experiments 9 & 10: Anomaly Detection
└── 📂 Pattern_and_Movement_Recognition/        # Experiment 11: Neural Networks
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Anaconda or Miniconda installed on your system.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/raghvendragoyal01/Pattern-Recognition-Experiments-models-from-Scratch-.git
   cd Pattern-Recognition-Experiments-models-from-Scratch-
   ```

2. **Create and activate a virtual environment:**
   ```bash
   conda create -n ml-labs python=3.10 -y
   conda activate ml-labs
   ```

3. **Install the required dependencies:**
   *(Most notebooks will install their own specific dependencies inline via pip, but standard ML packages are recommended)*
   ```bash
   pip install jupyter pandas numpy matplotlib seaborn scikit-learn tensorflow opencv-python
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Navigate to the respective experiment directory to run the interactive notebooks!

---

## 💡 Highlights

- **From Scratch Implementations:** Several algorithms (including U-Net) are built natively to provide deep conceptual understanding.
- **Rich Visualizations:** Comprehensive EDA, learning curves, loss graphs, and PCA/t-SNE/UMAP embeddings are provided across the notebooks.
- **Real-World Applications:** Focus on interdisciplinary data, mapping algorithmic theory directly to practical biological, visual, and sequential data.

<div align="center">
  <br>
  <i>Crafted with ❤️ for the pursuit of Artificial Intelligence</i>
</div>
