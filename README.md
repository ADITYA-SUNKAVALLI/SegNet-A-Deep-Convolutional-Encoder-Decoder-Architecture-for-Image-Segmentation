# SegNet-A-Deep-Convolutional-Encoder-Decoder-Architecture-for-Image-Segmentation


# Biomedical Image Segmentation using SegNet

This project implements **SegNet**, a deep convolutional encoder–decoder architecture for pixel-wise image segmentation.

The network predicts a segmentation mask by classifying each pixel into foreground or background.

---

## 🚀 Features
- Implementation of SegNet architecture
- Encoder–decoder CNN
- Pooling index based upsampling
- Works for biomedical / microscopy images
- GPU compatible
- Easy training and inference

---

## 🧠 Model Summary

SegNet is composed of two main parts:

### Encoder
- Series of convolution + batch normalization + ReLU
- Followed by max pooling
- Stores pooling indices

### Decoder
- Uses stored pooling indices to upsample
- Recovers spatial resolution
- Produces dense pixel predictions

### Final Layer
- Pixel-wise classification using softmax / sigmoid

---

## 🎯 Why SegNet?
Compared to traditional CNNs:
- Better boundary reconstruction  
- Memory efficient  
- Designed for semantic segmentation  

Widely used in:
- medical imaging  
- autonomous driving  
- satellite imagery  

---

## 📂 Dataset

The dataset should contain paired images and masks.

Expected format:

dataset/
images/
masks/


Add your dataset link here:  
👉 ADD_DATASET_LINK

---

## 💾 Pretrained Weights

Download weights from:  
👉 ADD_MODEL_LINK

Place inside:
