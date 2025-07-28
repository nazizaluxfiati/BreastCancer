## KLASIFIKASI KANKER PAYUDARA MENGGUNAKAN CNN

Proyek ini bertujuan untuk mengembangkan model klasifikasi gambar histopatologi kanker payudara menggunakan algoritma Convolutional Neural Network (CNN). Model dirancang untuk membedakan antara jaringan jinak (benign) dan ganas (malignant) berdasarkan data citra digital. Studi ini juga mencakup evaluasi kinerja model menggunakan metrik klasifikasi dan visualisasi hasil pelatihan.

### 🧠 FITUR UTAMA

Klasifikasi gambar histopatologi menjadi benign dan malignant
Pemrosesan dan augmentasi gambar menggunakan OpenCV & Keras ImageDataGenerator
Pelatihan model CNN dengan lapisan konvolusi dan pooling
Visualisasi hasil pelatihan (akurasi dan loss)
Evaluasi model dengan metrik akurasi, precision, recall, dan F1-score
📁 STRUKTUR PROYEK

### BreastCancer-Classification/
├── README.md
├── requirements.txt
├── cnnbreastcancer.py
├── dataset/
│   ├── benign/
│   └── malignant/
├── results/
│   ├── accuracy_loss_plot.png
│   └── classification_report.txt

### 🧬 DATASET

Sumber Data: Kaggle - Breast Histopathology Images
Jumlah Data: Ribuan gambar beresolusi 50x50 piksel
Kelas:
benign: jaringan payudara tidak ganas
malignant: jaringan kanker payudara
Format: Gambar berformat PNG

### 📝 LISENSI

Proyek ini dilisensikan di bawah MIT License — silakan digunakan, dimodifikasi, atau dikembangkan secara bebas dengan tetap mencantumkan atribusi yang sesuai.
