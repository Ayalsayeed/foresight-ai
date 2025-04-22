# FurSight AI 🐱
Cat Facial Recognition to Reunite Lost Pets

## 💡 Overview
FurSight AI uses deep learning and computer vision to identify cats from facial features—helping reunite lost pets with their families.

## 📂 Dataset
- Real-world cat face images
- Preprocessing: resized to 224x224, normalized
- Augmented with random flip, rotation, zoom
- Split: 80% train / 10% val / 10% test

## 🧠 Model
- Architecture: ResNet50 (pretrained on ImageNet)
- Loss: Categorical Crossentropy
- Optimizer: Adam
- Accuracy: 92.3% on validation

## 🏋️‍♀️ Train
```python
# In Colab
# Run all training cells
