# UTS MPML - Clustering Analysis

> Nama: Hilal Azhar Fawaz  
> NIM: 23611077  
> Mata Kuliah: Modern Prediction and Machine Learning

## 🧠 Deskripsi Proyek
Fokus utama proyek adalah menerapkan teknik **Clustering** pada data pendidikan dan ekonomi di Provinsi Jawa tengah. Tiga metode clustering yang digunakan adalah:

- **K-Means Clustering** dengan eksplorasi nilai `k` dari 1 hingga 10.
- **DBSCAN** untuk deteksi pola berdasarkan densitas.
- **Hierarchical Clustering** (Agglomerative) untuk struktur pohon klaster.

## 📊 Dataset

Data yang digunakan terdiri dari beberapa sumber dan disimpan dalam folder `Dataset/`. Dataset ini telah dibersihkan dan diproses sebelum digunakan untuk pelatihan model.
- `data_cleaned.csv`: Data hasil preprocessing
- `data_normalized.csv` : Data hasil normalisasi dengan StandardScaler
- `data_economic.csv`: Data indikator ekonomi
- `data_education.csv`: Data indikator pendidikan
- `data_location.csv`: Informasi lokasi dan geospasial

## 🛠️ Cara Menjalankan

1. Pastikan Anda memiliki Python 3.10+ dan Jupyter Notebook.
2. Untuk bagian preprocessing, jalankan notebook di folder Notebook:
   `Notebook/preprocessing.ipynb`
3. Untuk bagian clustering, jalankan notebook di masing-masing folder Clustering:
   - `Clustering/K_Means/kmeans.ipynb`
   - `Clustering/DBSCAN/dbscan.ipynb`
   - `Clustering/Hierarchical/hierarchical.ipynb`
4. Untuk memilih cluster optimal, jalankan notebook di folder Notebook:
   `Notebook/comparison.ipynb`

## 🧾 Lisensi

Proyek ini disusun untuk keperluan pembelajaran dan evaluasi akademik.
