<h1 align="center">🐣 Chicken Gender Detection with AI</h1>
<p align="center">A machine learning project designed to determine the gender of chicks before hatching using synthetic image and sound data.</p>

<div align="center">
  <img src="https://img.shields.io/badge/Type-Research--based-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Tech-Python%20%7C%20PyTorch%20%7C%20AI-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/ML%20Type-Image%20%2B%20Sound%20Classification-informational?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Experimental-yellow?style=flat-square"/>
</div>

---

## 📌 Overview

This project focuses on predicting the gender of chicks before hatching using AI. It uses:
- 🧬 Simulated ultrasound images
- 🎤 Audio signals of chick embryo movement
- 🧠 Convolutional Neural Networks (CNN) & Spectrogram analysis

---

## 💡 Motivation

In poultry farming, early detection of gender helps optimize resource allocation. This project aims to automate this process and reduce costs and inefficiencies.

---

## 🔧 Tech Stack

| Category      | Technologies                      |
|---------------|-----------------------------------|
| 🐍 Language     | Python                           |
| 🧠 Frameworks   | PyTorch, Librosa, OpenCV         |
| 📊 Data Format  | Simulated Ultrasound + Audio WAV |
| 📦 Tools        | Pandas, NumPy, Matplotlib        |
| 🧪 Notebook     | Jupyter                          |

---

## 🧪 Workflow

```mermaid
graph TD;
  Data[📁 Synthetic Ultrasound + Audio]
  Data --> Preprocess[🧹 Preprocessing]
  Preprocess --> CNN[🧠 CNN Model + Spectrogram Classifier]
  CNN --> Output[📈 Chick Gender Prediction]
