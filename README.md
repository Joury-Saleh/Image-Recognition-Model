#  Image Recognition Model using Teachable Machine

A lightweight and efficient image classification pipeline powered by a pre-trained Keras model exported from Google's [Teachable Machine](https://teachablemachine.withgoogle.com/). This project demonstrates how to load, preprocess, and predict image categories using a deep learning model in Python.

---

##  Overview

This repository contains:

- A Keras `.h5` model exported from Teachable Machine
- A label mapping file (`labels.txt`)
- A Python script for image prediction
- Example usage and setup instructions

The script accepts a static image, resizes and normalizes it, feeds it into the model, and returns the predicted class along with its confidence score.

---


##  Requirements

- Python ≥ 3.8 < 3.11
- TensorFlow = 2.12.1 (includes Keras)
- Pillow
- NumPy

### Install with pip:

```bash
pip install tensorflow==2.12.1



