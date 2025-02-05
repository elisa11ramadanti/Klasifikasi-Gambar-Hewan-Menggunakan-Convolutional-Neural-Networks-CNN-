# Klasifikasi Gambar Hewan Menggunakan Convolutional Neural Networks (CNN)

## Deskripsi Proyek
Proyek ini bertujuan untuk membangun model **Convolutional Neural Network (CNN)** untuk mengklasifikasikan gambar hewan ke dalam tiga kategori: **cats (kucing)**, **dogs (anjing)**, dan **tigers (harimau)**. Dataset yang digunakan terdiri dari 15.000 gambar yang diambil dari Kaggle. Dataset ini terbagi menjadi dua folder utama: `training_set` untuk data pelatihan dan `test_set` untuk data pengujian, yang masing-masing berisi gambar dari tiga kelas berbeda.

## Dataset
- **Sumber**: Kaggle - [Dataset klasifikasi gambar hewan](https://www.kaggle.com/datasets/nicopalv/dataset-klasifikasi-gambar-hewan)
- **Total Gambar**: 15.000
- **Kelas**:
  - **Cats** : Gambar kucing.
  - **Dogs** : Gambar anjing.
  - **Tigers** : Gambar harimau.
- **Struktur Folder**:
  - `training_set/` : Berisi gambar untuk pelatihan model.
  - `test_set/` : Berisi gambar untuk pengujian model.

### Struktur Dataset
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

## Contoh Gambar dari Setiap Kelas
- **Cats Class**
  ![Cats](https://github.com/user-attachments/assets/edeb443a-3c46-4d87-81e4-978f695985ec)

- **Dogs Class**
  ![Dogs](https://github.com/user-attachments/assets/bdf71bfe-c0ab-45b4-8954-d18d2f3ebb64)

- **Tigers Class**
  ![Tigers](https://github.com/user-attachments/assets/4f2e4763-c4a0-4bff-a604-893f958be69c)

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
