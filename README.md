# Deepfake Detection Pipeline

A nine module forensic Python pipeline for detecting GAN generated deepfake images, evaluated on ProGAN, BigGAN, and CycleGAN datasets.

Found k=20 features optimal for AdaBoost, reaching 87.20% mean AUC. Delivered as a 16 slide forensic report as part of a semester project.

## Contents

* `deepfake_pipeline.ipynb`, full forensic pipeline: feature extraction, feature selection, model training, and evaluation across multiple GAN sources
