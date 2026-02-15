# SegNet-A-Deep-Convolutional-Encoder-Decoder-Architecture-for-Image-Segmentation


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


 dataset link here:  
👉 https://drive.google.com/drive/folders/1UDopC9FF7uGiOzr7UElgcJ1aGCQAakeG?usp=drive_link

---

## 💾 Pretrained Weights

Download weights from:  
👉 https://drive.google.com/file/d/19bnxSR9uco-PWLIwLCc3iTq7Fb2tqU_D/view?usp=drive_link

⚙️ Installation
Clone the repository
git clone https://github.com/ADITYA-SUNKAVALLI/SegNet-A-Deep-Convolutional-Encoder-Decoder-Architecture-for-Image-Segmentation.git
cd SegNet-A-Deep-Convolutional-Encoder-Decoder-Architecture-for-Image-Segmentation

Create virtual environment (recommended)
Windows
python -m venv venv
venv\Scripts\activate

Linux / Mac
python -m venv venv
source venv/bin/activate

Install dependencies
pip install torch torchvision numpy matplotlib opencv-python tqdm

