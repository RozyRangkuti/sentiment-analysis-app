# sentiment-analysis-app

# Sentimen Analisis Review Aplikasi Google Play Store Pluang

## Bussiness Understanding
Analisis sentimen, sebagian dari klasifikasi teks, bertujuan untuk mengidentifikasi dan mengevaluasi opini, sikap, atau emosi yang terkandung dalam teks. Topik ini bisa menjadi alat yang sangat berguna baik dalam memahami pandangan pelanggan, tanggapan publik terhadap suatu peristiwa, maupun sentimen pasar terhadap suatu merek atau produk.

## Bussiness Problem
Analisis sentimen merupakan salah satu aspek penting dalam pemrosesan bahasa alami yang memungkinkan pengidentifikasian otomatis terhadap kecenderungan ulasan pengguna, apakah bersifat positif, negatif, atau netral. Proyek ini bertujuan membantu memahami umpan balik pengguna secara lebih mendalam dan mendukung pengambilan keputusan yang lebih baik dalam pengembangan serta peningkatan aplikasi Pluang.

## Project Scope
Topik yang dipilih haruslah sesuai dengan etika dan norma, serta tidak boleh mengandung unsur kontroversial atau isu-isu sensitif yang dapat menimbulkan masalah. Selain itu, harus mematuhi kebijakan dan pedoman dari platform sumber data dan menghindari tindakan yang dapat dianggap sebagai pencurian data. Dengan memahami pentingnya penghormatan terhadap etika dan kebijakan saat melakukan analisis sentimen, Saya siap untuk melangkah maju dalam proyek ini. Dengan kreativitas dan ketelitian, Saya akan dapat mempelajari data teks dari platform yang dipilih, serta menghasilkan wawasan yang berharga mengenai sentimen dan opini yang terkandung di dalamnya.

Berdasarkan cakupan proyek tersebut, Saya membutuhkan beberapa resource dan tool, yaitu:

- Data review aplikasi pluang dari google play store [(ulasan aplikasi pluang)](ulasan_aplikasi_pluang.csv);
- Bahasa pemrograman Python sebagai tool utama kita dalam proyek ini; serta
- Berbagai library pendukung untuk pengolahan data dan pengembangan model machine learning.

## Setup Environment - Anaconda

1. Clone Repository
   ```bash
   git clone https://github.com/RozyRangkuti/sentiment-analysis-app.git
   ```

2. Buka Terminal Anaconda, jalankan perintah berikut untuk membuat environment baru
   ```bash
   conda create --name myenv python=3.11
   ```
   
3. Aktifkan virtual environment dengan menjalankan perintah berikut ini
   ```bash
   conda activate myenv
   ```
   
4. Install semua requirements di dalam file "requirements.txt"
   ```bash
   pip install -r requirements.txt
