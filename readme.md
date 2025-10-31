# ✍️ Handwritten Text Recognition (HTR) in Python

## 📌 Overview
This project implements a Python-based Handwritten Text Recognition (HTR) system using deep learning. It takes scanned or photographed handwritten images and converts them into machine-readable text.

## 🚀 Features
- Recognizes handwritten text from images
- Preprocessing pipeline: grayscale, thresholding, resizing
- CNN + RNN + CTC-based architecture (or Tesseract OCR if using classical approach)
- Supports single-line or multi-line handwriting
- Outputs plain text or JSON

## 🛠️ Requirements
- Python 3.7+
- `numpy`, `opencv-python`, `matplotlib`
- `tensorflow` or `pytorch` (if using deep learning)
- `tesseract` (optional for classical OCR)

Install dependencies:
```bash
pip install -r requirements.txt
