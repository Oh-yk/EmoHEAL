# EmoHEAL: A Fusion-Based Framework for Emotion Recognition Using Wearable Sensors

Here is the PyTorch implementation of the EmoHEAL model. EmoHEAL is a lightweight deep learning architecture that uses wrist sensor data and achieves 72.35% accuracy on the K-EmoCon dataset, making it suitable for IoT applications in smartwatches.

# Architectures
1. TCN+CA-SA+GRU Fusion
2. TCN+GRU Fusion
3. TCN+xLSTM
4. TCN+MHA
5. TCN+Transformer Encoder
6. ResNet + GRU Fusion

# Dataset
You can request the dataset from [K-Emocon](https://zenodo.org/records/3931963). Place the dataset in the `dataset` folder.

# Requirements
Dependencies can be installed using the following command:
```
conda env create -f EmoHEAL.yml
```