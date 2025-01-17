
# Pengembangan Model Klasifikasi Tipe Kendaraan

Proyek ini bertujuan untuk mengembangkan sistem klasifikasi kendaraan otomatis menggunakan teknik Deep Learning. Model yang digunakan adalah Convolutional Neural Networks (CNN), ResNet50, dan VGG19 untuk meningkatkan akurasi klasifikasi tipe kendaraan berdasarkan gambar.

## Deskripsi
Sistem ini dirancang untuk mengenali tipe kendaraan (Mobil Biasa, Bus, dan Truk) dengan memanfaatkan dataset gabungan dari Stanford Cars Dataset serta hasil scraping dari internet. Model terbaik, ResNet50, mencapai akurasi 95%, menjadikannya solusi efektif untuk aplikasi pengelolaan tol otomatis dan sistem transportasi cerdas.

## Hasil Utama
- **Model Terbaik:** ResNet50 dengan akurasi 95%
- **Kategori Kendaraan:**
  - Mobil Biasa (SUV, Sedan, Hatchback)
  - Bus
  - Truk

## Metodologi
1. **Dataset:** Gabungan Stanford Cars Dataset dan hasil scraping (1.961 gambar)
2. **Preprocessing:** Normalisasi, resizing, augmentasi data (rotasi, flipping, zoom, dsb.)
3. **Model yang Digunakan:**
   - **ResNet50:** Akurasi tertinggi (95%)
   - **VGG19:** Akurasi 93%
   - **CNN:** Baseline (29%)
4. **Evaluasi:** Menggunakan confusion matrix dan metrik akurasi.

## Teknologi yang Digunakan
- Python
- TensorFlow
- Keras
- Google Colab (runtime GPU)
