# Modul 1 - Text Processing Pipeline

Proyek ini menggabungkan Praktikum 1–5 untuk eksplorasi korpus, preprocessing teks, analisis linguistik, dan model n-gram pada dataset komentar MBG.

## Struktur Folder

```text
BAIQ NADYA FAIRUZ QUTRATU'AIIN_240306057_MODUL1/
├── modul1_final.ipynb
├── dataset/
│   └── dataset.csv
├── output/
│   └── dataset_preprocessed.csv
└── README.md
```

## Menjalankan Notebook

1. Buka `modul1_final.ipynb` di VS Code atau Jupyter.
2. Pilih kernel Python yang memiliki dependensi notebook.
3. Jalankan semua sel dari atas ke bawah.
4. Notebook membaca `dataset/dataset.csv` dan menyimpan hasil preprocessing ke `output/dataset_preprocessed.csv`.

Notebook menggunakan NLTK, pandas, Matplotlib, Sastrawi, dan Stanza. Resource NLTK serta model Bahasa Indonesia Stanza perlu tersedia pada environment yang dipakai.

## Dataset

`dataset/dataset.csv` adalah salinan dataset MBG dengan kolom teks utama `text_original`. `output/dataset_preprocessed.csv` berisi `text_original`, `clean_text`, dan `processed_text`.

Hasil POS tagging dan dependency parsing merupakan prediksi model dan perlu ditinjau berdasarkan konteks teks.
