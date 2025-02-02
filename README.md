# Project Title: TATA_ASSESSMENT

---

## Overview

This repository contains the code and experiments for training and evaluating a CNN model on the CIFAR-10 dataset. The project explores different hyperparameter combinations, including learning rates, optimizers (Adam and SGD), and batch sizes, to optimize the model's performance. The goal is to analyze how these hyperparameters affect the model's training loss, validation accuracy, and test accuracy.

---

## Project Details

- **Dataset**: CIFAR-10
- **Model**: Convolutional Neural Network (CNN)
- **Optimization Techniques**: Adam, SGD optimizers
- **Hyperparameters Tuned**: Learning rate, batch size, optimizer choice

---

## Results Summary

### Best Configuration:
- **Learning Rate**: 0.001
- **Optimizer**: Adam
- **Batch Size**: 32
- **Test Accuracy**: 86.34%
- **Validation Accuracy**: 89.42%

---

## Links

- **Colab Link**: [CIFAR-10 CNN Experiment on Colab](https://colab.research.google.com/drive/17v3w4i1FPCUaRH4Rzp-N7OszwevOpz_j#scrollTo=v6yp_Y8v9AwA)
- **WandB Link**: [WandB CIFAR-10 CNN Experiment](https://wandb.ai/chaithanyakadiyala777-indiatimes/cifar10-cnn?nw=nwuserchaithanyakadiyala777)

---

## Conclusion

- The optimal configuration for this task is the Adam optimizer with a learning rate of 0.001 and batch size of 32.
- Hyperparameter tuning significantly impacts model performance, particularly in learning rate and optimizer selection.
