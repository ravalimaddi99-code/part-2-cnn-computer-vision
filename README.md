# Part 2: CNN Computer Vision
## Manufacturing Defect Classification

## Problem Statement
Image Classification of manufacturing defects using CNN.

## Dataset
- Total images: 480
- Classes: 4 (normal, scratch, dent, stain)
- Images per class: 120 (perfectly balanced)

## Model Architecture
- 3 Convolution + MaxPooling blocks
- Flatten layer
- Dense layer (128 neurons)
- Dropout (0.5)
- Output layer (4 classes - Softmax)

## Results
- Train Accuracy: 87.95%
- Validation Accuracy: 90.91%

## Business Use Case
Manufacturing quality inspection using CNN to automatically detect product defects.