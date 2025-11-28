# IndicSign
https://drive.google.com/file/d/1epHvFPd2VlkaSUbxTSdakk8xkCvnp9ZA/view?usp=sharing

**Bridging the communication gap with cutting-edge deep learning techniques.**

## Overview

The Indian Sign Language Interpreter is an AI-powered system designed to classify and translate Indian Sign Language (ISL) hand gestures into text. Leveraging the ResNet-50 architecture, the model accurately identifies 35 distinct hand gestures, covering the English alphabets (A-Z) and digits (0-9). This project aims to promote inclusivity and assist individuals with hearing and speech impairments by enabling seamless communication with non-sign language users.

## Features
- **High Accuracy:** Uses ResNet-50 with fine-tuning for robust gesture classification.
- **Data Augmentation:** Ensures model robustness across diverse environments with techniques like resizing, flipping, and rotation.
- **Transfer Learning:** Efficiently repurposes pre-trained ResNet-50 for ISL-specific tasks.
- **Scalable Applications:** Designed for deployment in mobile devices, assistive systems, and IoT integrations.

## Goals and Objectives
- Develop a reliable system for classifying 35 hand gesture categories.
- Enhance inclusivity by bridging communication gaps.
- Leverage advanced AI techniques, including transfer learning and data augmentation.
- Prepare for real-world applications like mobile apps and edge devices.

## Implementation
### Dataset Preparation
- Images of 35 hand gesture classes from Kaggle.
- Augmentation techniques: random resizing, flipping, rotation, and normalization.

### Model Architecture
- **ResNet-50 Backbone:** Pre-trained on ImageNet, fine-tuned for ISL classification.
- **Custom Classifier:** Dense layers with ReLU, dropout for regularization, and softmax for multi-class outputs.

### Training and Optimization
- **Optimizer:** Adam for adaptive learning rates.
- **Loss Function:** CrossEntropyLoss for accuracy measurement.
- **Learning Scheduler:** ReduceLROnPlateau for dynamic rate adjustments.
- **Epochs:** 10, with validation at each stage.

### Testing and Deployment
- Achieved high accuracy on the test dataset.
- Model saved as `best_resnet50_model.pth` and ready for deployment.

## Future Prospects
- **Real-Time Recognition:** Enable live video processing for dynamic gestures.
- **Device Integration:** Smart gloves and AR glasses compatibility.
- **Multilingual Support:** Expand to other regional and global sign languages.
- **Mobile App:** Build accessible applications for broader use.

## Conclusion
This project showcases the potential of deep learning in addressing societal challenges. By translating ISL gestures into text, it empowers individuals with hearing and speech impairments, fostering inclusivity and accessibility.

---

**Transforming communication with AI for an inclusive future.**
