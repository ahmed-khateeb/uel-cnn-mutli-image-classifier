# CIFAR-100 CNN Model Comparison

This repository contains modular and reproducible implementations of three deep convolutional neural network architectures applied to the CIFAR-100 image classification task. The models compared in this study are:

- ✅ ResNet18
- ✅ DenseNet121
- ✅ EfficientNet-B0 (with pretrained weights)

Each model was trained using PyTorch and evaluated based on accuracy, training time, and generalization performance.

---

## 🔬 Project Overview

This repository supports a research study titled:

**“A Comparative Study of CNN Architectures, Hyperparameter Tuning, and Data Augmentation Strategies for Multi-Class Image Classification on CIFAR-100”**

The objective is to compare:
- Performance of different CNN models
- Impact of hyperparameter tuning (optimizers, learning rates, batch sizes)
- Effectiveness of data augmentation
- Benefits of transfer learning

---

## 🗂 File Structure

- `ResNet.ipynb` – Training and evaluation of ResNet18 on CIFAR-100
- `DenseNet.ipynb` – Training and evaluation of DenseNet121
- `EfficientNet.ipynb` – Training of EfficientNet-B0 using resized 224x224 inputs and pretrained weights

Each notebook includes:
- Data preprocessing (with and without augmentation)
- Model definition
- Training and validation loops
- Accuracy logging and result plots

---

## 💻 Environment

- Python 3.12.7
- PyTorch (with `torchvision`)
- Trained on Apple M3 Max using Metal Performance Shaders (MPS)

---

## 📊 Key Results

| Model           | Test Accuracy | Validation Accuracy |
|----------------|----------------|----------------------|
| ResNet18        | 47.5%          | 49%                  |
| DenseNet121     | 53.3%          | 54%                  |
| EfficientNet-B0 | **77.9%**      | **78%**              |

---

## 📘 Reference

This repository supports the academic assignment for the **CN7023 - Artificial Intelligence & Machine Vision** module.

The accompanying research paper can be provided upon request.

---

## 📎 License

This code is for academic use only.
