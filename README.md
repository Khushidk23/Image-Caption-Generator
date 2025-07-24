# 🖼️ Image Caption Generator using Deep Learning

This project implements an end-to-end deep learning pipeline that takes an input image and generates a relevant, human-like caption. It combines **Convolutional Neural Networks (CNNs)** for image feature extraction with **Recurrent Neural Networks (RNNs)** or LSTMs for language generation.

---

## 🔍 Project Highlights

- 🧠 Uses pre-trained CNN (e.g., VGG16/ResNet) for image feature extraction
- 📝 LSTM or GRU-based decoder for caption generation
- 🗂️ Trained on the **Flickr8k / Flickr30k / MS COCO** dataset
- 📈 Includes BLEU score evaluation
- 🎯 Supports training, inference, and beam search captioning

---

## 🗂️ Dataset

- Public datasets like:
  - 📸 [Flickr8k](https://www.kaggle.com/datasets/adityajn105/flickr8k)
  - 🖼️ [MS COCO](https://cocodataset.org/)
- Each image is associated with 5 human-written captions

---

## 📌 Technologies & Libraries

- Python
- TensorFlow / Keras
- NumPy & Pandas
- Matplotlib
- Pillow (PIL)
- NLTK

---

## ⚙️ Installation

```bash
git clone https://github.com/Khushidk23/Image-Caption-Generator.git
cd Image-Caption-Generator
pip install -r requirements.txt
