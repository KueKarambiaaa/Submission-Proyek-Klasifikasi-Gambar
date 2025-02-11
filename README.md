# Submission-Proyek-Klasifikasi-Gambar

Deskripsi Proyek
Proyek ini adalah bagian dari submission kelas Dicoding untuk membangun model klasifikasi gambar menggunakan Convolutional Neural Network (CNN). Model dilatih dengan dataset The Simpsons Characters untuk mengenali karakter dari serial animasi tersebut.

Fitur Proyek
Menggunakan arsitektur Sequential dengan Conv2D dan Pooling Layer.
Preprocessing dataset (normalisasi dan augmentasi).
Model dilatih dengan 80% data latih dan 20% data uji.
Evaluasi dengan plot akurasi dan loss model.
Model disimpan dalam format:
SavedModel
TensorFlow Lite (TF-Lite)
TensorFlow JS (TFJS)
Teknologi yang Digunakan
Python
TensorFlow
Matplotlib
NumPy
Struktur Proyek
bash
Copy
Edit
├── data/
│   ├── train/
│   └── test/
├── model/
│   ├── saved_model/
│   ├── tflite_model/
│   └── tfjs_model/
├── notebooks/
│   └── klasifikasi-gambar.ipynb
├── README.md
└── requirements.txt
