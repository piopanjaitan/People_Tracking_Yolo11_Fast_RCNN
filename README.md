import os

# People Tracking (Yolo11 vs Faster R-CNN)
People Tracking (Yolo11 vs Faster R-CNN)
Project 2 - Kelompok A (Raden Saleh) - Indonesia AI

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

## 💻 Instalasi & Penggunaan
1. **Clone Repository**:
   ```bash
   git clone [https://github.com/piopanjaitan/People_Tracking_Yolo11_Fast_RCNN.git](https://github.com/piopanjaitan/People_Tracking_Yolo11_Fast_RCNN.git)
   cd People_Tracking_Yolo11_Fast_RCNN

2. **Instalasi Dependency**:
    ```bash
    pip install torch torchvision ultralytics gradio opencv-python supervision
    ```

3. **Menjalankan Proyek**:

   Buka salah satu file notebook di Google Colab atau Jupyter Notebook, lalu jalankan semua sel untuk mengaktifkan UI Gradio di bagian akhir.

## 📓 Notebook & Resource
Proyek ini dikembangkan menggunakan Google Colab:
* **Yolo 11 Tracking**: [Buka di Colab](https://colab.research.google.com/drive/12kvlenxPjWbawyeSDyq_dmP5O_zg-pAq#scrollTo=IU_hECmVLzuz)
* **Faster R-CNN Tracking**: [Buka di Colab](https://colab.research.google.com/drive/1iSfFe895cwZdtI9UvfM-RqVq91HYSA8I#scrollTo=K6ZJfDqJYLU5)

## 📱 Demo in HuggingFace

<a href="https://huggingface.co/spaces/piopanjaitan/people_tracking_yolo11_and_faster_rcnn" target="_blank">Demo Here</a>

## 📂 Struktur Folder
```bash
People_Tracking_Yolo11_Fast_RCNN/
├── People_Tracking_YOLO11.ipynb
├── People_Tracking_Faster_RCNN.ipynb
├── README.md
└── examples/
    ├── input_video.mp4
    └── output_result.jpg