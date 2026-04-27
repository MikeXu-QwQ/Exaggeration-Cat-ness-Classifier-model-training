# Exaggeration-Cat-ness-Classifier-model-training
how i trained 2 models
This project investigates how visual models encode graded levels of “catness” exaggeration.

The task is formulated as a regression problem, where the model predicts a continuous catness score from 0.0 (Non‑Cat) to 1.0 (Prototype Cat).

Two backbone architectures are compared under identical training conditions:

ResNet‑50 (CNN-based)
Vision Transformer (ViT‑Base, Transformer-based)

AIMODEL
https://huggingface.co/microsoft/resnet-50
https://huggingface.co/google/vit-base-patch16-224

The goal is to analyze:

Prediction behavior
Representation collapse
Feature space geometry differences
