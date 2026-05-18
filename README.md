# 🫀 Heart Disease Prediction - Data Preprocessing & Experimentation (MLOps)

<p align="center">
  <a href="https://github.com/xebec51">
    <img src="https://img.shields.io/badge/GitHub-xebec51-blue?logo=github" />
  </a>
  <a href="https://www.linkedin.com/in/rinaldiruslan">
    <img src="https://img.shields.io/badge/LinkedIn-rinaldiruslan-0A66C2?logo=linkedin&logoColor=white" />
  </a>
  <a href="https://www.instagram.com/rinaldiruslan/">
    <img src="https://img.shields.io/badge/Instagram-rinaldiruslan-E4405F?logo=instagram" />
  </a>
  <a href="https://www.tiktok.com/@rinaldiruslan">
    <img src="https://img.shields.io/badge/TikTok-rinaldiruslan-000000?logo=tiktok&logoColor=white" />
  </a>
  <br/>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" />
  </a>
  <img src="https://img.shields.io/badge/MLOps-Data%20Engineering-orange" />
</p>

---

🌐 **Submission dari Kelas**:
[Membangun Sistem Machine Learning - Dicoding](https://www.dicoding.com/academies/713)

🏆 **Status Kelulusan**: Lulus dengan Predikat Memuaskan (Bintang 5 / Advanced)

### 🎓 Sertifikat Kelulusan Resmi
Sebagai bukti pemenuhan kriteria kompetensi tingkat lanjut (*Advanced*), berikut adalah sertifikat kelulusan dari Dicoding. *Klik pada gambar di bawah:*

<div style="display: flex; flex-direction: row; gap: 8px; justify-content: center; align-items: center;">
  <a href="https://www.dicoding.com/certificates/RVZK0M64MZD5" style="flex: 0 0 auto;">
    <img src="assets/sertifikat_page_1.jpg" style="width: 48%; max-width:360px; height: auto; display: block;" alt="Sertifikat Halaman 1" />
  </a>
  <a href="https://www.dicoding.com/certificates/RVZK0M64MZD5" style="flex: 0 0 auto;">
    <img src="assets/sertifikat_page_2.jpg" style="width: 48%; max-width:360px; height: auto; display: block;" alt="Sertifikat Halaman 2" />
  </a>
</div>

---

## 🔗 Ekosistem Proyek (End-to-End MLOps)

Proyek ini merupakan bagian dari arsitektur MLOps berskala produksi yang dipecah menjadi 4 repositori terpisah untuk merepresentasikan siklus kerja *microservices* dan integrasi sistem yang utuh:

1. 📊 **[Eksperimen & Preprocessing Data](https://github.com/xebec51/eksperimen_sml_rinaldi)** 📍 *(Anda berada di sini)*
2. 🧠 **[Pembangunan Model & MLflow Tracking](https://github.com/xebec51/mlsystem-heart-disease-rinaldi)**
3. ⚙️ **[Workflow CI/CD & Dockerization](https://github.com/xebec51/workflow-ci-rinaldi)**
4. 📈 **[Monitoring & Logging (Prometheus/Grafana)](https://github.com/xebec51/heart-disease-monitoring-rinaldi)**

---

## 📌 Deskripsi Proyek

Repositori ini adalah fondasi awal dari seluruh ekosistem prediksi penyakit jantung (*Heart Disease*). Fokus utamanya adalah melakukan eksplorasi data secara mendalam (EDA), penanganan *missing values*, pembersihan data, hingga proses transformasi dan standardisasi (*feature scaling*).

Nilai tambah (*Advanced*) utama dari repositori ini adalah implementasi **Data Preprocessing Automation** yang ditenagai oleh **GitHub Actions**. Setiap kali terdapat modifikasi atau pembaruan pada data mentah (`data_raw`), alur kerja otomatis pipeline akan terpicu untuk memproses ulang data secara mandiri menjadi data siap latih (`data_processed`) tanpa intervensi manual.

---

## 🚀 Key Highlights

* ✅ **Eksperimen Notebook:** Melakukan tahapan eksplorasi data (EDA) komprehensif, visualisasi korelasi fitur, dan *prototyping* langkah-langkah pembersihan data.
* ✅ **Automasi Script (`automate_Rinaldi.py`):** Mengonversi seluruh langkah eksperimen dari notebook menjadi skrip Python yang siap berjalan otomatis di lingkungan produksi.
* ✅ **GitHub Actions Integration:** Pipeline otomatisasi yang mampu melakukan *commit* dan *push* dataset olahan terbaru secara langsung ke dalam repositori saat *trigger* push data mentah aktif.
* ✅ **Data Split & Scaling:** Otomatisasi pembagian dataset menjadi *Train-Test set* dengan rasio 80:20 serta standardisasi fitur numerik menggunakan objek `StandardScaler`.

---

## 📂 Struktur Proyek

```bash
.
├── .github/workflows/
│   └── preprocessing.yml      # GitHub Actions CI Automation Preprocessing
├── assets/
│   ├── sertifikat_page_1.jpg  # File Gambar Sertifikat Hal 1
│   └── sertifikat_page_2.jpg  # File Gambar Sertifikat Hal 2
├── data_raw/
│   └── heart_disease.csv      # Dataset Medis Pasien (Mentah)
├── preprocessing/
│   ├── automate_Rinaldi.py    # Script Pemrosesan Otomatis (Python)
│   ├── Eksperimen_Rinaldi.ipynb
│   └── data_processed/        # Direktori Output Dataset Siap Latih (Otomatis)
└── README.md

```

---

## ▶️ Cara Menjalankan Automasi Lokal

### 1. Clone repository

```bash
git clone [https://github.com/xebec51/eksperimen_sml_rinaldi.git](https://github.com/xebec51/eksperimen_sml_rinaldi.git)

```

### 2. Masuk ke folder proyek

```bash
cd eksperimen_sml_rinaldi

```

### 3. Install dependencies

```bash
pip install pandas scikit-learn

```

### 4. Jalankan script automasi pemrosesan data

```bash
python preprocessing/automate_Rinaldi.py

```

---

## 🛠️ Teknologi yang Digunakan

* Python
* Pandas & NumPy
* Scikit-learn
* Jupyter Notebook
* GitHub Actions (CI Data Pipeline)

---

## 👤 Author

**Muh. Rinaldi Ruslan**

* 💻 GitHub: https://github.com/xebec51
* 💼 LinkedIn: https://www.linkedin.com/in/rinaldiruslan
* 📸 Instagram: https://www.instagram.com/rinaldiruslan/
* 🎵 TikTok: https://www.tiktok.com/@rinaldiruslan

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah **MIT License**.