# GPU-Accelerated Deep Learning with TensorFlow & Keras

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![NVIDIA](https://img.shields.io/badge/NVIDIA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)](https://www.nvidia.com/en-us/deep-learning-ai/)

A hands-on lab that explains the difference between CPUs and GPUs and demonstrates how to leverage GPU acceleration to significantly speed up deep learning model training in TensorFlow.

---

## 📖 Lab Overview

You've likely heard of CPUs (Central Processing Units) and GPUs (Graphics Processing Units). While historically associated with gaming, GPUs are now a cornerstone of modern deep learning. Their ability to perform massive **parallel computations** makes them exceptionally well-suited for the matrix and tensor operations that define neural networks.

This advantage becomes evident when training models on large datasets. What might take hours or days on a CPU can often be completed in minutes on a GPU. In this lab, you will learn the practical steps to utilize a GPU to accelerate your `tensorflow` and `keras` workflows. 🚀

---

## 🔬 CPU vs. GPU for Deep Learning

The fundamental difference lies in their architecture and design philosophy:

* **CPU (The Generalist):** A CPU has a small number of powerful cores optimized for sequential tasks. It's a jack-of-all-trades, designed to handle a wide variety of operations one after another very quickly.
* **GPU (The Specialist):** A GPU has thousands of smaller, specialized cores. It's designed to handle a massive number of parallel tasks simultaneously. This is perfect for deep learning, where the same operation (e.g., matrix multiplication) is performed across thousands of data points at once.



---

## 🎯 Learning Objectives

After completing this lab, you will be able to:

1.  Understand the architectural differences between CPUs and GPUs and why this matters for deep learning.
2.  Verify that TensorFlow can detect and access an available GPU.
3.  Write Keras code that automatically utilizes a GPU for model training.
4.  Quantify the performance gain by comparing the training time of a model on a CPU versus a GPU.

---
