# Computer Vision

This course introduces the fundamentals of Computer Vision, progressing from basic image processing to modern deep learning techniques. It explores real-world applications such as object analysis and human-related tasks through both theory and hands-on projects.

## Assignments / Projects

The main problem was to predict the perceived age from a face image while minimizing the Mean Absolute Error (MAE) and reducing bias across gender, age range, ethnicity, and facial expression. The dataset was highly imbalanced, which added an additional challenge to achieving fair and accurate predictions. This problem was split into two tasks:

### 1. [Automatic Age Perception – Intelligent Data Augmentation](./task1_data_augmentation_.ipynb/)

**Main challenge:**
- Handling multiple sensitive attributes simultaneously  

**Approach & Model:**
- Balanced data augmentation
- ResNet-50 architecture
- TensorFlow / Keras
- Pretrained on face data
- Trained using 70% of the dataset
- Highly structured and guided starter notebook

The accompanying **(PDF report)[./Computer-Vision-Task-1-Report.pdf/]** includes the model design, training strategy, evaluation metrics, bias analysis, results, and conclusions.

---

### 2. [Automatic Age Perception – Custom Loss Function (No Augmentation)](task2_customloss.ipynb)

> **Note:** The `.ipynb` file contains the complete implementation, but due to size and widget-rendering issues, the **outputs are best viewed in the [HTML file](https://nbviewer.org/github/irisvukovic/MSc-DataScience-UB/blob/main/Computer-Vision/task2_customloss.html)**.  

Reduce age prediction error and subgroup bias **without data augmentation**, by integrating fairness directly into the training objective.

**Main challenge:**
- Creating a **custom loss function** that places higher weight on under-represented groups

**Approach & Model:**
- Vision Transformer (ViT)
- PyTorch
- Pretrained on ImageNet
- 100% of the training data used
- Weighted/custom loss to reduce bias
- More experimental and less guided than Task 1

The accompanying **(PDF report)[./Computer-Vision-Task-2-Report.pdf/]** details the custom loss formulation, training setup, results, fairness analysis, and final conclusions.

