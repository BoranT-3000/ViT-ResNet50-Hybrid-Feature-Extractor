# ViT-ResNet50-Hybrid-Feature-Extractor
Combined Vision Transformer and ResNet50 Feature Extractors for Enhanced Image Classification



## Introduction

This project was inspired by the paper '[A Hybrid ResNet-ViT Approach to Bridge the Global and Local Features for Myocardial Infarction Detection](https://www.nature.com/articles/s41598-024-54846-8).' The hybrid model combines the strengths of Vision Transformers (ViT) and ResNet50, enhancing the accuracy of image classification tasks by balancing global and local feature extraction.

## Dataset

For this project, the [hongrui/mammogram_v_1](https://huggingface.co/datasets/hongrui/mammogram_v_1) dataset from HuggingFace was used. This dataset provides a collection of mammogram images that are suitable for training and evaluating the hybrid ViT and ResNet50 model for image classification tasks.

## Features

- **Vision Transformer (ViT)**: Provides a broad perspective to understand the overall context of an image.
- **ResNet50**: Focuses on learning detailed and local features within an image.
- **Hybrid Approach**: Combines the strengths of ViT and ResNet50 for improved image classification performance.
- **Adaptable to Various Datasets**: The model can be fine-tuned and adapted to various datasets beyond mammograms.



---------------------------------------------------------

Vision Transformer (ViT) ve ResNet50'yi birleştirmek, görüntü sınıflandırma işlemlerinde güçlü bir performans sunar. ViT, görüntünün genel bağlamını anlamak için geniş bir bakış açısı sağlarken, ResNet50 ise detayları ve yerel özellikleri daha iyi öğrenir. Bu iki modelin birleşimi, her iki yaklaşımın avantajlarını bir araya getirerek daha doğru ve etkili sonuçlar elde edilmesini sağlar.

Bu yaklaşımı, 'A Hybrid ResNet-ViT Approach to Bridge the Global and Local Features for Myocardial Infarction Detection' makalesinden esinlenerek geliştirdim.

Bu proje için HuggingFace'ten hongrui/mammogram_v_1 veri setini kullandım. Bu veri seti, hibrit Vision Transformer (ViT) ve ResNet50 modelinin görüntü sınıflandırma görevleri için eğitilmesi ve değerlendirilmesi amacıyla kullanılmıştır.


## License(Lisans)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
