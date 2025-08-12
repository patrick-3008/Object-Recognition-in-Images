# CIFAR-10 Image Classification

## 📌 Overview
This project focuses on building and evaluating machine learning models for the **CIFAR-10** dataset — a widely recognized benchmark in the computer vision community for object recognition tasks.

**CIFAR-10** is a subset of the *80 Million Tiny Images* dataset and contains:
- **60,000** color images (32×32 pixels)
- **10 object classes** (6,000 images per class)
- Split into **50,000 training images** and **10,000 test images**

The dataset was collected by **Alex Krizhevsky**, **Vinod Nair**, and **Geoffrey Hinton**.

For more details on dataset performance benchmarks, see [Rodrigo Benenson's classification results page](http://rodrigob.github.io/are_we_there_yet/build/classification_datasets_results.html).

---

## 🎯 Goal
The main objective of this repository is to:
- Explore **different machine learning models** for CIFAR-10 classification
- Compare their performance against **Kaggle's CIFAR-10 leaderboard**
- Provide a clean, reproducible training and evaluation pipeline

---

## 📂 Dataset
You can access the CIFAR-10 dataset from:
- [Kaggle CIFAR-10 Competition](https://www.kaggle.com/c/cifar-10)
- [Official CIFAR-10 Dataset Page](https://www.cs.toronto.edu/~kriz/cifar.html)

---

## 📊 Results
| Model       | Accuracy | Notes                  |
|-------------|----------|------------------------|
| Simple CNN  | 78%      | Baseline model         |
| ResNet50    | 93%      | Pretrained on ImageNet |
| DenseNet121 | 94%      | Fine-tuned             |

---

## 🏆 Kaggle Leaderboard
Submit your predictions to the [Kaggle CIFAR-10 Competition](https://www.kaggle.com/c/cifar-10) and see how your score compares to others.

---

## 📜 References
- Krizhevsky, A., & Hinton, G. (2009). Learning multiple layers of features from tiny images.
- [Kaggle CIFAR-10 Competition](https://www.kaggle.com/c/cifar-10)
- [Rodrigo Benenson’s Benchmark](http://rodrigob.github.io/are_we_there_yet/build/classification_datasets_results.html)
