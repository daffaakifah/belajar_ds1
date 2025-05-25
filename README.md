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
   - Pastikan file prediksi.py, model.pkl., preprocessor.pkl, serta file dataset berada dalam folder/direktori yang sama.
   - Jalankan aplikasi dashboard dengan perintah berikut di terminal atau command prompt:
       ```
       streamlit run prediksi.py
       ```
 3. Menjalankan Dashboard di Looker Studio
    - Menyiapkan data yang perlu digunakan yaitu dataset 'employee_data_filled.csv'
    - Buka looker studio (lookerstudio.google.com)
    - Upload dataset bisa digunakan dengan opsi pilihan Upload File CSV.
    - Pilih Visualisasi yang cocok dan sesuai dengan data.
    - Dashboard yang sudah dibuat dengan langkah-langkah di atas dalam proyek ini dapat diakses [dashboard-proyek-hr](https://lookerstudio.google.com/reporting/170f23f5-de4f-409b-b40b-f53061891f13).
    - Dashboard Looker Studio ini akan menjadi pusat monitoring real-time untuk HR Attrition berdasarkan data prediksi dan data historis.

## Business Dashboard
#### Ringkasan Dashboard
Dashboard ini menganalisis data dari 1.470 karyawan di Jaya Jaya Maju untuk mengidentifikasi faktor-faktor yang mempengaruhi tingkat attrition. Dari total tersebut, 14,5% karyawan (sekitar 213 orang) telah keluar dari perusahaan. Dashboard ini juga menampilkan berbagai metrik dan visualisasi yang membantu memahami pola attrition dan faktor risiko yang terkait. Dashboard dapat diakses pada link berikut [dashboard-proyek-hr](https://lookerstudio.google.com/reporting/170f23f5-de4f-409b-b40b-f53061891f13).

#### Faktor Utama Attrition
Beberapa faktor utama yang berpengaruh signifikan terhadap attrition adalah:
- Lembur (OverTime): Karyawan yang melakukan lembur memiliki risiko attrition yang lebih tinggi, menunjukkan adanya tekanan kerja yang berkontribusi pada keputusan keluar.
- Pendapatan Bulanan (Monthly Income): Karyawan dengan pendapatan bulanan lebih rendah cenderung memiliki risiko keluar yang lebih tinggi.
- Usia (Age): Rata-rata usia karyawan adalah 37 tahun, dengan kelompok usia muda hingga menengah lebih rentan mengalami attrition.
- Tingkat Jabatan (Job Level) dan Kepuasan Kerja (Job Satisfaction) juga berperan penting dalam menentukan risiko attrition.
- Status Pernikahan (Marital Status): Karyawan yang berstatus lajang (single) menunjukkan tingkat attrition yang lebih tinggi dibandingkan yang menikah atau bercerai.

#### Distribusi dan Pola Karyawan Keluar
- Kelompok Usia 25–35 tahun merupakan kelompok yang paling banyak mengalami attrition.
- Status Pernikahan Single memiliki tingkat attrition tertinggi, yaitu sekitar 54,9%.
- Karyawan yang melakukan lembur memiliki risiko lebih tinggi untuk keluar.
- Karyawan dengan gaji bulanan di bawah rata-rata $4.643,62 juga lebih berisiko mengalami attrition.

#### Job Role dan Risiko
- Bidang pekerjaan dengan attrition tertinggi adalah posisi dengan tingkat jabatan rendah hingga menengah, terutama di level 1 dan 2.
- Job Satisfaction dan Job Involvement yang rendah juga berkorelasi dengan tingkat attrition yang lebih tinggi.

#### Tren Risiko
- Semakin tinggi usia, pendapatan, dan lama bekerja di perusahaan, semakin kecil kemungkinan karyawan untuk keluar.
- Hal ini menandakan pentingnya strategi retensi untuk karyawan senior dan berpengalaman agar tetap bertahan di perusahaan.
- Lama bekerja dengan manajer saat ini juga berpengaruh, di mana karyawan yang sudah lama dengan manajer cenderung memiliki risiko
  attrition yang lebih rendah.
  
#### Prediksi Model
##### Performa model
Model yang digunakan menggunakan algoritma Random Forest mneghasilkan akurasi 0.8679, dengan hasil prediksi sebagai berikut: <br>
![image](https://github.com/user-attachments/assets/a3b1a6b3-50d1-46ac-aafb-a5ad9302cfb0)

##### Contoh tampilan hasil prediksi berdasarkan faktor di prediksi.py
![image](https://github.com/user-attachments/assets/a2310b82-8a4a-433c-85f1-ee869d4a0be2)
![image](https://github.com/user-attachments/assets/12893b77-0e0c-4afb-91c3-8e4f9e9d239f)
![image](https://github.com/user-attachments/assets/8ec26f35-3adf-4afb-8879-d9db8d9c9523)

## Conclusion
### Faktor penting
Beberapa penting yang dihasilkan dari pemodelan:
- OverTime (Lembur) adalah faktor paling signifikan yang memengaruhi attrition. Karyawan yang sering lembur memiliki risiko keluar yang jauh lebih tinggi, menandakan tekanan kerja yang berkontribusi pada keputusan mereka.
- MonthlyIncome (Gaji Bulanan) yang rendah, usia muda, dan TotalWorkingYears (lama bekerja secara keseluruhan) yang pendek juga meningkatkan kemungkinan karyawan untuk keluar.
- Faktor lain seperti YearsAtCompany (lama bekerja di perusahaan saat ini), YearsInCurrentRole (lama di posisi saat ini), dan - 
- YearsWithCurrManager (lama bekerja dengan manajer saat ini) juga berpengaruh, meskipun tidak dominan.
- Distribusi attrition menunjukkan bahwa kelompok usia 25–35 tahun dan karyawan dengan status pernikahan single memiliki tingkat attrition tertinggi (sekitar 54,9%).
- Posisi dengan tingkat jabatan rendah hingga menengah (Job Level 1 dan 2) serta tingkat kepuasan kerja dan keterlibatan kerja yang rendah juga berkorelasi dengan risiko attrition yang lebih tinggi.
- Semakin tinggi usia, pendapatan, dan lama bekerja di perusahaan, semakin kecil kemungkinan karyawan keluar, menandakan pentingnya strategi retensi untuk karyawan senior dan berpengalaman.

### Model yang digunakan
Model yang digunakan ini unggul dalam mengenali karyawan yang tidak keluar (kelas 0) dengan akurasi tinggi, namun masih perlu peningkatan dalam mendeteksi karyawan yang berisiko keluar (kelas 1) karena recall yang relatif rendah. Untuk selanjutnya dapat dilakukan optimisasi model agar menghasilkan model yang lebih akurat.

### Rekomendasi Action Items 
Rekomendasi action items untuk mengurangi attrition dan meningkatkan retensi karyawan:
1. Kurangi Lembur yang Berlebihan <br>
Karyawan yang sering lembur berisiko lebih tinggi untuk keluar. Perusahaan dapat menawarkan pelatihan manajemen dan efisiensi waktu.
2. Tinjau Struktur Gaji <br>
Gaji yang rendah meningkatkan risiko attrition. Pastikan struktur gaji kompetitif dan tambahkan insentif atau bonus untuk meningkatkan kepuasan finansial karyawan. <br>
3. Optimalkan Beban Kerja dan Pengembangan Karir <br>
Seimbangkan beban kerja dan berikan peluang pengembangan serta promosi internal agar karyawan tidak merasa stagnan dan lebih termotivasi untuk bertahan.
4. Implementasi Model Prediktif untuk Pemantauan  <br>
Integrasikan model Random Forest ke dalam dashboard HR untuk memantau risiko attrition secara real-time dan memberikan peringatan dini agar tindakan proaktif dapat diambil. Serta terus menerus untuk mengupdate data dan melatih model agar menghasilkan hasil prediksi yang lebih baik.

### Kesimpulan akhir
Keseluruhan proyek ini menganalisis dan mengidentifikasi lembur, gaji rendah, usia muda, dan pengalaman kerja yang singkat sebagai faktor utama risiko karyawan keluar. Model Random Forest memberikan prediksi terbaik dengan akurasi tinggi untuk karyawan yang bertahan, namun perlu peningkatan dalam mendeteksi yang berisiko keluar. Rekomendasi utama adalah mengurangi lembur berlebihan, meninjau struktur gaji, mengoptimalkan pengembangan karir, dan mengimplementasikan model prediktif untuk pemantauan risiko attrition secara real-time
