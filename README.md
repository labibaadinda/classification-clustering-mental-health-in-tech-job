# Clustering dan Classification mengenai Mental Health di Tech Job

## Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis data dari **OSMI Mental Health in Tech Survey 2016** untuk memahami kondisi kesehatan mental di kalangan pekerja teknologi. Dengan lebih dari **1400 responden**, dataset ini mencerminkan pandangan, pengalaman, dan tantangan yang dihadapi oleh para profesional IT terkait kecemasan, depresi, stres, serta akses terhadap dukungan psikologis di tempat kerja.

Dalam proyek ini, saya menerapkan teknik **clustering** untuk mengelompokkan responden berdasarkan pola jawaban yang serupa, seperti tingkat stres, kenyamanan membicarakan kesehatan mental, dan dukungan dari perusahaan. Selain itu, saya juga menggunakan metode **klasifikasi** untuk memprediksi kemungkinan seseorang mengalami gangguan mental tertentu berdasarkan atribut-atribut yang tersedia.

---

## **1. Perkenalan Dataset**

Dataset ini dapat diakses melalui [Kaggle](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016) dan berisi data terkait prevalensi masalah kesehatan mental di kalangan pekerja teknologi.

* **Sumber Dataset**: [Mental Health in Tech Survey 2016](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016)

* **Deskripsi Dataset**:
  Dataset ini mencakup informasi tentang prevalensi kecemasan, depresi, stres, dan pencarian perawatan kesehatan mental di kalangan pekerja di sektor teknologi. Responden dibagi berdasarkan status pekerjaan mereka, perusahaan tempat mereka bekerja, pengalaman mereka dengan masalah kesehatan mental, dan sumber daya yang mereka akses.

---

## **2. Instalasi dan Persiapan**

Untuk menjalankan proyek ini, Anda perlu menginstal beberapa pustaka Python yang digunakan dalam analisis dan pemodelan.

### Langkah-langkah Instalasi:

1. **Kloning Repositori (Opsional)**:
   Jika proyek ini disediakan melalui GitHub, Anda dapat mengkloning repositori terlebih dahulu:

   ```bash
   git clone https://github.com/labibaadinda/classification-clustering-mental-health-in-tech-job
   cd classification-clustering-mental-health-in-tech-job
   ```

2. **Buat Lingkungan Virtual (Opsional)**:
   Anda dapat membuat lingkungan virtual untuk menghindari konflik dependensi dengan proyek lainnya. Berikut adalah cara membuat dan mengaktifkan lingkungan virtual menggunakan `venv`:

   * **Membuat Lingkungan Virtual**:

     ```bash
     python3 -m venv venv
     ```

   * **Mengaktifkan Lingkungan Virtual**:

     * Untuk Windows:

       ```bash
       venv\Scripts\activate
       ```
     * Untuk macOS/Linux:

       ```bash
       source venv/bin/activate
       ```

3. **Instal Pustaka Tambahan (Opsional)**:
   Jika ada pustaka yang perlu diinstal secara manual, Anda dapat menginstalnya menggunakan pip:

   ```bash
   pip install pandas seaborn matplotlib sklearn yellowbrick
   ```

---

## **3. Kesimpulan**

Hasil clustering menunjukkan bahwa terdapat dua kelompok utama dalam dataset. Dengan model ini, kita bisa lebih memahami faktor-faktor yang mempengaruhi kesehatan mental pekerja teknologi dan bagaimana mereka merespons masalah tersebut di tempat kerja. Secara keseluruhan, model Random Forest menunjukkan performa yang paling konsisten dan efektif, sementara Decision Tree juga memberikan hasil yang stabil dan memadai dalam klasifikasi data.

---

### Referensi

* [OSMI Mental Health in Tech Survey 2016 Dataset](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016)
* [Scikit-learn Clustering](https://scikit-learn.org/stable/modules/clustering.html)

---
