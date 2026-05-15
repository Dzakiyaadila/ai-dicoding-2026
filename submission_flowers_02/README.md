# Flower Classification CNN

## 📋 Deskripsi Proyek
Proyek ini bertujuan untuk mengklasifikasikan 5 jenis bunga menggunakan Convolutional Neural Network (CNN).

## 🌸 Kelas Bunga
- Lilly
- Lotus  
- Orchid
- Sunflower
- Tulip

## 📊 Dataset
- Sumber: https://github.com/Dzakiyaadila/flower-datasets.git
- Total gambar: 5000 gambar (1000 per kelas)
- Split data: 70% train, 15% validation, 15% test

## 🏗️ Arsitektur Model
- 4 layer Conv2D + BatchNormalization + MaxPooling2D
- GlobalAveragePooling2D
- Dense layer dengan Dropout untuk mencegah overfitting

## 📈 Hasil Evaluasi
- Test Accuracy: 88.93%
- Test Loss: 1.0944

## 📦 Format Model
- SavedModel (TensorFlow)
- TF-Lite (Mobile/Embedded)
- TFJS (Browser/JavaScript)

## 🛠️ Cara Menjalankan
1. Install dependencies: `pip install -r requirements.txt`
2. Buka notebook: `jupyter notebook notebook.ipynb`
3. Jalankan semua cell secara berurutan

## 👤 Author
[Ganti dengan nama Anda]

## 📅 Tanggal
[Ganti dengan tanggal sekarang]
