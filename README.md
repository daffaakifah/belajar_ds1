# Proyek Akhir: Menyelesaikan Permasalahan Human Resources <br>
### Perusahaan Jaya Jaya Maju - Oleh Daffa Akifah

## Business Understanding
Jaya Jaya Maju adalah perusahaan multinasional yang berdiri sejak tahun 2000 dengan lebih dari 1000 karyawan yang tersebar di seluruh negeri. Meskipun sudah cukup besar, perusahaan menghadapi tantangan serius dalam pengelolaan sumber daya manusia, terutama tingginya tingkat attrition (karyawan keluar) yang mencapai lebih dari 10%.

Manajer HR ingin memahami faktor-faktor yang mempengaruhi tingginya attrition rate dan membutuhkan dashboard bisnis untuk memonitor faktor-faktor tersebut secara real-time. Dataset karyawan disediakan untuk analisis dan pembuatan model prediksi attrition.

### Permasalahan Bisnis
Berikut adalah permasalahan bisnis utama yang dihadapi oleh Jaya Jaya Maju dan menjadi fokus penyelesaian dalam proyek ini: <br>
1. Tingginya Tingkat Attrition Karyawan <br>
Jaya Jaya Maju mengalami tingkat attrition (karyawan keluar) yang cukup tinggi, yaitu lebih dari 10%. Hal ini berdampak negatif pada stabilitas tenaga kerja, produktivitas, dan biaya operasional perusahaan.

2. Kurangnya Pemahaman Faktor Penyebab Attrition <br>
Manajemen HR belum memiliki pemahaman yang mendalam mengenai faktor-faktor utama yang menyebabkan karyawan memutuskan untuk keluar, sehingga sulit untuk mengambil tindakan preventif yang tepat.

3. Kesulitan dalam Monitoring dan Pengambilan Keputusan <br>
Manajer HR kesulitan dalam memonitor kondisi karyawan secara real-time dan mengidentifikasi kelompok karyawan yang berisiko tinggi untuk keluar tanpa alat bantu visualisasi dan analisis yang efektif.

4. Kebutuhan Model Prediksi untuk Identifikasi Risiko <br>
Perusahaan membutuhkan model prediksi yang dapat mengidentifikasi karyawan yang berpotensi tinggi untuk keluar, sehingga dapat dilakukan intervensi lebih awal untuk meningkatkan retensi.

5. Optimalisasi Pengelolaan Sumber Daya Manusia <br>
Dengan memahami faktor-faktor yang mempengaruhi attrition dan memonitor kondisi karyawan secara efektif, perusahaan dapat mengoptimalkan strategi pengelolaan SDM, termasuk kebijakan remunerasi, pengembangan karir, dan kesejahteraan karyawan.

### Cakupan Proyek
#### Tujuan Penyelesaian
1. Mengidentifikasi faktor-faktor utama yang mempengaruhi attrition karyawan di Jaya Jaya Maju.
2. Membuat dashboard interaktif yang menampilkan indikator kunci dan visualisasi terkait attrition untuk membantu manajemen HR dalam pengambilan keputusan.
3. Mengembangkan model prediksi attrition yang akurat untuk mengantisipasi risiko kehilangan karyawan.
4. Memberikan rekomendasi strategis berbasis data untuk menurunkan tingkat attrition dan meningkatkan retensi karyawan.

#### Batasan Proyek
1. Proyek ini fokus pada analisis data historis dan prediksi attrition berdasarkan data yang tersedia.
2. Tidak mencakup intervensi langsung atau implementasi kebijakan HR.
3. Model prediksi bersifat probabilistik dan memerlukan evaluasi berkelanjutan untuk akurasi di masa depan.

#### Hasil yang Diharapkan
1. Pemahaman yang lebih baik tentang faktor-faktor yang mempengaruhi attrition karyawan.
2. Dashboard monitoring yang efektif dan mudah digunakan oleh manajemen HR.
3. Model prediksi yang dapat membantu mengidentifikasi karyawan berisiko tinggi untuk keluar.
4. Rekomendasi strategis berbasis data untuk meningkatkan retensi karyawan.

### Persiapan
#### Sumber data
Dataset yang digunakan dalam proyek ini adalah dataset dari instruksi submission yaitu dataset [Jaya Jaya Maju](https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee).

#### Setup environment
1. Menjalankan notebook.ipynb <br>
   - File notebook.ipynb dapat dijalankan dalam visual studio atau IDE sejenis.
   - Pastikan dependensi, paket, dan library yang dibutuhkan telah tersedia. Daftar dependensi lengkap dapat dilihat pada file 
     requirements.txt yang disediakan dalam proyek. <br>
   - Jalankan seluruh isi notebook.ipynb di Google Colab atau IDE sejenis.
     Ini akan menampilkan hasil analisis data, temuan, dan insight yang diperoleh dari eksplorasi dan pemodelan data.
2. Menjalankan prediction.py <br>
   - File prediksi.py dapat dijalankan dalam visual studio atau IDE sejenis.
   - Pastikan semua dependensi sudah terinstal, terutama streamlit. Gunakan perintah berikut untuk instalasi jika belum:
       ```
        pip install -r requirements.txt
        ```
   - Jalankan aplikasi dashboard dengan perintah berikut di terminal atau command prompt:
       ```
       streamlit run prediksi.py
       ```
 3. Menjalankan Dashboard di Looker Studio
    - Menyiapkan data yang perlu digunakan yaitu dataset 'employee_data_filled.csv'
    - Buka looker studio (lookerstudio.google.com)
    - Upload dataset bisa digunakan dengan opsi pilihan Upload File CSV.
    - Pilih Visualisasi yang cocok dan sesuai dengan data.
    - Dashboard yang sudah dibuat dengan langkah-langkah di atas dapat diakses [dashboard-proyek-hr](https://lookerstudio.google.com/reporting/170f23f5-de4f-409b-b40b-f53061891f13).
    - Dashboard Looker Studio ini akan menjadi pusat monitoring real-time untuk HR Attrition berdasarkan data prediksi dan data historis.

## Business Dashboard

Jelaskan tentang business dashboard yang telah dibuat. Jika ada, sertakan juga link untuk mengakses dashboard tersebut.

## Conclusion

Jelaskan konklusi dari proyek yang dikerjakan.

### Rekomendasi Action Items (Optional)

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

- action item 1
- action item 2
