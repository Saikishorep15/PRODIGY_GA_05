# 🎨 PRODIGY_GA_05 – Neural Style Transfer using PyTorch

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg">
  <img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-red.svg">
  <img src="https://img.shields.io/badge/Computer%20Vision-Neural%20Style%20Transfer-green.svg">
  <img src="https://img.shields.io/badge/Status-Completed-success.svg">
  <img src="https://img.shields.io/badge/Internship-Prodigy%20InfoTech-orange.svg">
</p>

## 📌 Overview

This project implements **Neural Style Transfer (NST)** using **PyTorch**. The application combines the content of one image with the artistic style of another to generate a stylized output image using a pre-trained deep learning model.

This project was developed as **Task-05** for the **Prodigy InfoTech Generative AI Internship**.

## 🎯 Objective

Develop a Neural Style Transfer application capable of applying the artistic style of one image to the content of another image using deep learning techniques.

## ✨ Features

- Neural Style Transfer
- Pre-trained VGG19 Feature Extractor
- Content and Style Image Processing
- Automatic Output Image Generation
- Clean Project Structure
- Beginner-Friendly Implementation

## 📂 Project Structure

```text
PRODIGY_GA_05
│
├── images
│   ├── content
│   │   └── content.jpg
│   │
│   ├── style
│   │   └── style.jpg
│   │
│   └── output
│       └── stylized_image.jpg
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```
## 🛠️ Technologies Used

- Python
- PyTorch
- TorchVision
- Pillow
- NumPy
- Matplotlib

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/<your-github-username>/PRODIGY_GA_05.git
```

Navigate to the project folder

```bash
cd PRODIGY_GA_05
```

Install dependencies

```bash
pip install -r requirements.txt
```
## ▶️ Usage

Place your images inside:

```text
images/content/content.jpg
images/style/style.jpg
```

Run the application

```bash
python app.py
```
## 📁 Output

The generated stylized image will be saved in:

```text
images/output/stylized_image.jpg
```
## 💻 Sample Console Output

```text
============================================================
          NEURAL STYLE TRANSFER
============================================================

Loading images...
Loading VGG19 model...

Style Transfer Completed Successfully!

Output saved to:
images/output/stylized_image.jpg
```
## 📚 Concepts Covered

- Neural Style Transfer
- Transfer Learning
- Feature Extraction
- Deep Learning
- Computer Vision
- Image Processing
- PyTorch

## 🚀 Future Improvements

- Interactive GUI using Streamlit
- Multiple Style Image Support
- High-Resolution Image Processing
- Adjustable Style Strength
- Batch Processing
- GPU Optimization

## 🎓 Internship Details

**Organization:** Prodigy InfoTech

**Domain:** Generative AI Internship

**Task:** Task-05 – Neural Style Transfer

## 👨‍💻 Author

**Meghana R**

GitHub: https://github.com/rmeghana375-lab

## 📄 License

This project is developed for educational purposes as part of the **Prodigy InfoTech Generative AI Internship**.