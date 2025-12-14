# KenaliCara - Temukan Gaya Belajarmu 🎓

![KenaliCara Logo](https://via.placeholder.com/150?text=KenaliCara) 
<!-- *Catatan: Ganti URL gambar di atas dengan logo aplikasi jika ada.* -->

**KenaliCara** adalah aplikasi berbasis AI yang dirancang untuk membantu siswa mengetahui gaya belajar mereka (Visual, Auditory, Atau Kinesthetic). Dengan memahami gaya belajar, siswa dapat menerapkan metode belajar yang lebih efektif, dan guru dapat merancang strategi pembelajaran yang lebih personal dan tepat sasaran.

## 🌟 Fitur Utama

*   **Klasifikasi Gaya Belajar AI**: Menganalisis input siswa menggunakan model Machine Learning (XGBoost) untuk menentukan gaya belajar dominan.
*   **Analisis Personal**: Memberikan penjelasan mendalam tentang karakteristik gaya belajar siswa.
*   **Rekomendasi Belajar**: Menyediakan tips dan trik belajar yang disesuaikan dengan hasil prediksi.
*   **Dashboard Guru** (Planned): Membantu guru memantau profil gaya belajar kelas untuk penyesuaian materi ajar.

## 🛠️ Teknologi yang Digunakan

Projek ini dibangun menggunakan teknologi web modern dan machine learning:

### Frontend (Client-Side)
*   **Framework**: [Next.js 16](https://nextjs.org/) (React 19)
*   **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
*   **UI Library**: [Radix UI](https://www.radix-ui.com/), Lucide React (Icons)
*   **HTTP Client**: Axios

### Backend (Server-Side & AI)
*   **Framework**: [FastAPI](https://fastapi.tiangolo.com/) (Python)
*   **Machine Learning**: [XGBoost](https://xgboost.readthedocs.io/), Scikit-learn
*   **Data Processing**: Pandas, Numpy

## 🚀 Instalasi & Penggunaan (Getting Started)

Ikuti langkah-langkah berikut untuk menjalankan aplikasi di komputer lokal Anda.

### Prasyarat
Pastikan Anda telah menginstal:
*   [Node.js](https://nodejs.org/) (versi 18+)
*   [Python](https://www.python.org/) (versi 3.9+)

### 1. Setup Backend (API)

Masuk ke direktori backend dan instal dependensi Python:

```bash
cd xgboostAPI

# (Opsional) Buat virtual environment
python -m venv venv
# Windows:
.\venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# Instal paket yang dibutuhkan
pip install -r requirements.txt

# Jalankan server
uvicorn main:app --reload
```
Server backend akan berjalan di `http://127.0.0.1:8000`.

### 2. Setup Frontend (Web App)

Buka terminal baru, masuk ke direktori frontend, dan jalankan server pengembangan:

```bash
cd kenalicara-fe

# Instal dependensi Node.js
npm install

# Jalankan server development
npm run dev
```
Buka `http://localhost:3000` di browser Anda untuk melihat aplikasi.

## 📁 Struktur Projek

*   `/kenalicara-fe`: Kode sumber aplikasi web (Frontend).
*   `/xgboostAPI`: Kode sumber API dan Model AI (Backend).

## 📄 Lisensi

Hak Cipta © 2025 Tim Pengembang KenaliCara.
Dibuat untuk tujuan pendidikan dan penelitian.
