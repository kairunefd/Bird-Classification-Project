
# Bird Species Classification using CNNs

This project evaluates and compares three different Convolutional Neural Network (CNN) architectures—**ResNet50, DenseNet121, and MobileNetV3** to classify 10 specific bird species.

## Project Overview

The goal is to identify the most suitable model for bird classification based on accuracy, Mean Average Precision (mAP), training efficiency, and model size.

### Bird Classes:

* Bald Eagle, Cockatoo, Crane, Flamingo, Great Grey Owl
* King Penguin, Ostrich, Peacock, Robin, Toucan

---

## Methodology

* **Data Split:** 8:1:1 (Train, Validation, Test).
* **Preprocessing:** All images resized to  pixels.
* **Training:** 30 Epochs per model.
* **Framework:** TensorFlow/Keras on Google Colab (T4 GPU).

### Models Evaluated:

1. **ResNet50:** Utilizes residual "skip" connections to train deeper networks effectively.
2. **DenseNet121:** Connects each layer to every other layer to improve feature reuse.
3. **MobileNetV3:** Optimized for mobile devices using depth-wise separable convolutions.

---

## How to Run

1. The `dataset_final` folder is in release v1.0.0.
2. Open the `.ipynb` notebook in Google Colab.
3. Ensure the Runtime type is set to **T4 GPU**.
4. Run all cells to replicate the training and visualization.
