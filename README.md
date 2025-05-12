# TensorFlow Object Detection API Example Of Usage

![Python](https://img.shields.io/badge/python-3.8-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.10-orange)

A TensorFlow-based object detection pipeline using the SSD ResNet50 V1 FPN 640x640 model.  
This project demonstrates how to set up, run, and use object detection with 
pre-trained models from the [TensorFlow Model Zoo](
https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md).

---

## 📌 Purpose

This repository provides a framework to:
- Perform object detection on images using TensorFlow 2.
- Use pre-trained models for inference and integrate them into custom applications.

> This project is intended for students studying computer vision.
> Each group (brigade) receives a specific object detection task listed below.

## 📋 Detection Task Variants for Student Groups

| Group № | Object to Detect | Additional Requirements                         |
|---------|------------------|-------------------------------------------------|
| 1       | Book             | Include images where a person is holding a book |
| 2       | Laptop           | Add frames where the screen is clearly visible  |
| 3       | Wallet           | Include both opened and closed wallet images    |
| 4       | Keyboard         | Add both full-size and mini keyboard examples   |
| 5       | Notebook         | Include images with handwritten text            |

## 📁 Repository Structure

```
ObjectDetectionTF/
├── annotations/            # Label map and annotation files
├── docs/                   # Documentation
├── exported-models/        # Trained and exported models
├── images/                 # Test images
├── models/                 # Training configs and checkpoints
├── pre-trained-models/     # Models from TensorFlow Model Zoo
├── scripts/                # Scripts for training, evaluation, inference
├── src/                    # Source Code for Using Pretrained Models
└──environment.yml          # Conda environment specification
```

---

## 📚 Documentation

- [Environment Setup](docs/environment_setup.md)
- [Run Demo](docs/demo.md)
- [Training Custom Object Detector](docs/training_custom_object_detector.md)
- [Model Validation](docs/validation.md)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Contact

Created by **_Kyrylo Oliinyk_**.

Feel free to reach out with any questions or suggestions.
