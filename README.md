# Plant Classification with Deep Learning

Proyek ini merupakan implementasi image processing dan klasifikasi citra tanaman menggunakan deep learning berbasis Softmax.

## 📁 Dataset

- Dataset: **Plant Classification** dari Kaggle.
- Total data asli: 30.000 gambar (30 kelas x 1000 gambar).
- Data dipangkas menjadi 5 kelas (total 5000 gambar) untuk efisiensi pemrosesan.
- Setelah augmentasi 5 kelas x 4000 gambar untuk menambah variasi.

## 🔄 Tahapan Proyek

1. **Data Preprocessing**:

   - Pemotongan dataset dari 30 ke 5 kelas.
   - Pembagian train/test split.

2. **Augmentasi Data**:

   - Rotasi, flipping, add brightness, bluring, shearing, dan warp shift.

3. **Modeling**:

   - Deep learning dengan output layer menggunakan **Softmax**.
   - Akurasi akhir: **94%** (0.94).

4. **Model Export**:

   - Model disimpan dalam format:
     - **TensorFlow.js** (`tfjs`)
     - **TensorFlow Lite** (`tflite`)

5. **Inference**:
   - Uji coba prediksi dari model hasil training.

## 🛠 Library yang Digunakan

- `tensorflow`, `keras`
- `numpy`, `pandas`
- `matplotlib`, `seaborn`
- `kaggle`, `os`, `shutil`
- `skicit-learn`
- `tensorflowjs`, `keras`

## 📌 Struktur Folder

```
.
├── Projek_Plant_Classification  # Notebook utama
├── requirements.txt             # Requirement
└── README.md
```

## 🚀 Cara Menjalankan

1. Clone repo:
   ```bash
   git clone https://github.com/Lahen194/ProyekImageProsessing-PlantClassification.git
   ```
2. Install dependensi:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan notebook Projek_Plant_Classification.

## 🎯 Tujuan Proyek

Mengklasifikasikan gambar tanaman secara efisien dengan dataset dari kaggle, dan menyimpan model dalam format multiplatform (tfjs dan tflite). Projek ini dilakukan untuk memenuhi penugasan pembelajaran 'Pengembangan Machine Learning' dicoding.

## 📌 Catatan

- Proyek ini hanya menganalisis 5 kelas dari keseluruhan dataset dalam kaggle.
- Projek ini berhasil mendapat 4 bintang dari reviewer tim Dicoding.
