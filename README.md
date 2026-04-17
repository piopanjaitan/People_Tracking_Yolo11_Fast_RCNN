import os

# Define the content for README.md
readme_content = """# People Tracking (Yolo11 vs Faster R-CNN)
Project 2 - Indonesia AI

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-ee4c2c.svg)](https://pytorch.org/)
[![Ultralytics](https://img.shields.io/badge/YOLO-v11-success.svg)](https://docs.ultralytics.com/)
[![Gradio](https://img.shields.io/badge/UI-Gradio-orange.svg)](https://gradio.app/)

## 📌 Deskripsi Proyek
Proyek ini merupakan implementasi sistem pelacakan orang (**People Tracking**) menggunakan dua pendekatan arsitektur *Deep Learning* yang berbeda: **YOLOv11** dan **Faster R-CNN**. Sistem ini mampu mendeteksi keberadaan orang dalam gambar maupun video dan memberikan ID unik untuk melacak pergerakan mereka.

Proyek ini bertujuan untuk membandingkan:
1. **YOLOv11**: Model deteksi *one-stage* yang sangat cepat dan efisien untuk pemrosesan video.
2. **Faster R-CNN**: Model deteksi *two-stage* yang mengutamakan akurasi deteksi objek.

## 🛠️ Fitur & Spesifikasi Teknis
* **Detection Models**: 
    * **YOLOv11**: Menggunakan library `ultralytics`.
    * **Faster R-CNN**: Menggunakan arsitektur berbasis `torchvision`.
* **Tracking System**: Pemberian ID unik (Tracker) untuk setiap objek yang terdeteksi.
* **Integrasi UI**: Antarmuka interaktif menggunakan **Gradio** untuk memudahkan upload file dan visualisasi hasil.
* **Output**: Mendukung pemrosesan data dalam format Gambar (`.jpg`, `.png`) dan Video (`.mp4`).

## 📓 Notebook & Resource
Proyek ini dikembangkan menggunakan Google Colab:
* **Yolo 11 Tracking**: [Buka di Colab](https://colab.research.google.com/drive/12kvlenxPjWbawyeSDyq_dmP5O_zg-pAq#scrollTo=IU_hECmVLzuz)
* **Faster R-CNN Tracking**: [Buka di Colab](https://colab.research.google.com/drive/1iSfFe895cwZdtI9UvfM-RqVq91HYSA8I#scrollTo=K6ZJfDqJYLU5)

## 📂 Struktur Folder
```bash
People_Tracking_Yolo11_Fast_RCNN/
├── People_Tracking_YOLO11.ipynb
├── People_Tracking_Faster_RCNN.ipynb
├── README.md
└── examples/
    ├── input_video.mp4
    └── output_result.jpg