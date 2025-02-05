# Klasifikasi-Gambar-Hewan-Menggunakan-Convolutional-Neural-Networks-CNN

## Deskripsi Proyek
Proyek ini bertujuan untuk membangun model **Convolutional Neural Network (CNN)** untuk mengklasifikasikan gambar hewan ke dalam tiga kategori: **cats (kucing)**, **dogs (anjing)**, dan **tigers (harimau)**. Dataset yang digunakan terdiri dari 15.000 gambar yang diambil dari Kaggle. Dataset ini terbagi menjadi dua folder utama: `training_set` untuk data pelatihan dan `test_set` untuk data pengujian, yang masing-masing berisi gambar dari tiga kelas berbeda.

## Dataset
- **Sumber**: Kaggle - [Dataset klasifikasi gambar hewan](https://www.kaggle.com/datasets/nicopalv/dataset-klasifikasi-gambar-hewan)
- **Total Gambar**: 15.000
- **Kelas**:
  - **cats** : Gambar kucing.
  - **dogs** : Gambar anjing.
  - **tigers** : Gambar harimau.
- **Struktur Folder**:
  - `training_set/` : Berisi gambar untuk pelatihan model.
  - `test_set/` : Berisi gambar untuk pengujian model.

- **Struktur Dataset**:

```plaintext
 dataset/
├── test_set/
│   ├── cats/
│   ├── dogs/
│   └── tigers/
├── training_set/
│   ├── cats/
│   ├── dogs/
│   └── tigers/
```

## Library dan Dependensi
Berikut adalah daftar library yang dibutuhkan untuk menjalankan proyek ini:
- TensorFlow
- NumPy
- Matplotlib
- OpenCV
- os
- shutil
- zipfile

Untuk menginstal semua dependensi yang diperlukan, jalankan perintah berikut:

```bash
pip install -r requirements.txt
```

## Referensi
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Kaggle Dataset](https://www.kaggle.com/datasets/nicopalv/dataset-klasifikasi-gambar-hewan)
- [TensorFlow.js Converter](https://www.tensorflow.org/js/tutorials)

## Penulis
**Elisa Ramadanti**
