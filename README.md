
# Adversarial Defense for Skin Cancer Classification

## Overview

This project explores **adversarially robust skin cancer classification** using deep learning techniques to improve resilience against AI-based adversarial attacks such as **Projected Gradient Descent (PGD)**. The goal was to evaluate how defensive strategies can improve model robustness while maintaining classification performance.

The project was implemented collaboratively and focuses on understanding the trade-off between **accuracy, robustness, and adversarial detectability** in medical image classification.

## Problem Statement

Deep learning models used in medical imaging can be vulnerable to **adversarial attacks**, where small perturbations in input images can significantly affect predictions. This project investigates defense strategies to improve the robustness of a skin cancer classification model against such attacks.

## Approach

The project implements a defense pipeline using:

* **PyTorch** for model development
* **CBAM (Convolutional Block Attention Module)** to improve feature attention
* **Adversarial Training** to improve robustness against attacks
* **PGD (Projected Gradient Descent) attacks** for robustness evaluation
* **OOD (Out-of-Distribution) Detection** to analyze adversarial detectability
* **Computer Vision and Deep Learning techniques** for medical image classification

## Key Objectives

* Improve robustness of skin cancer classification models against adversarial attacks
* Evaluate trade-offs between clean accuracy and robustness
* Analyze adversarial detectability using OOD experiments
* Explore attention mechanisms for better feature representation

## Tech Stack

* Python
* PyTorch
* Computer Vision
* Deep Learning
* Adversarial Machine Learning

## Contributors

* Rashika Rathore
* Diya Saini

## Note

This project was developed as an implementation and experimental study of adversarial defense mechanisms in medical image classification.
