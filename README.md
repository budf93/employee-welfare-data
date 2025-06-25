Analisis Data Kesejahteraan dan Retensi Karyawan

Proyek ini bertujuan untuk melakukan analisis mendalam terhadap dataset kesejahteraan karyawan yang berisi lebih dari 9.000 catatan. Tujuan utamanya adalah untuk mengidentifikasi faktor-faktor kunci yang memengaruhi kompensasi, atrisi (perpindahan karyawan), dan kepuasan kerja. Wawasan yang dihasilkan dari analisis ini dapat digunakan sebagai dasar pengambilan keputusan strategis dalam manajemen sumber daya manusia.

🎯 Tujuan Analisis
Mengidentifikasi Pendorong Utama Atrisi: Memahami mengapa karyawan memutuskan untuk meninggalkan perusahaan.

Menganalisis Faktor Kompensasi: Menentukan variabel apa yang paling signifikan memengaruhi pendapatan bulanan karyawan.

Melakukan Segmentasi Karyawan: Mengelompokkan karyawan ke dalam beberapa profil berbeda untuk strategi manajemen talenta yang lebih tertarget.

🔑 Temuan Utama dari Analisis
Berdasarkan Exploratory Data Analysis (EDA) dan pemodelan yang telah dilakukan, berikut adalah beberapa temuan kunci:

1. Faktor-Faktor Pendorong Atrisi Karyawan
Model prediktif yang dibangun berhasil mengidentifikasi beberapa faktor yang secara signifikan meningkatkan kemungkinan seorang karyawan untuk keluar:

Lembur (OverTime): Karyawan yang sering bekerja lembur memiliki kecenderungan lebih tinggi untuk meninggalkan perusahaan. Ini bisa menjadi indikator beban kerja yang tidak seimbang atau burnout.

Tingkat Pekerjaan (JobLevel): Karyawan pada level jabatan yang lebih rendah menunjukkan tingkat atrisi yang lebih tinggi, menandakan kemungkinan adanya keterbatasan dalam jalur karir atau kompensasi di level awal.

Status Pernikahan (MaritalStatus): Karyawan dengan status lajang (Single) memiliki tingkat atrisi yang lebih tinggi dibandingkan dengan yang sudah menikah atau bercerai.

Departemen: Terdapat beberapa departemen, seperti Human Resources dan Technical Degree, yang menunjukkan tingkat atrisi yang lebih tinggi dibandingkan departemen lain.

2. Penentu Utama Kompensasi Karyawan
Analisis regresi untuk memprediksi pendapatan bulanan (MonthlyIncome) menunjukkan bahwa:

Tingkat Pekerjaan (JobLevel): Merupakan faktor paling dominan dalam menentukan besaran gaji. Kenaikan level jabatan secara langsung berkorelasi positif dengan kenaikan pendapatan yang signifikan.

Total Pengalaman Kerja (TotalWorkingYears): Pengalaman kerja yang lebih lama juga berkontribusi positif terhadap pendapatan bulanan, meskipun pengaruhnya tidak sebesar level jabatan.

3. Segmentasi Profil Karyawan (Clustering)
Dengan menggunakan K-Means Clustering, kami berhasil mengidentifikasi 3 profil atau segmen karyawan yang berbeda:

Cluster 0: Karyawan Junior & Berkembang

Karakteristik: Pendapatan bulanan dan level jabatan relatif rendah, namun memiliki persentase kenaikan gaji (PercentSalaryHike) yang cenderung moderat hingga tinggi.

Interpretasi: Segmen ini kemungkinan besar diisi oleh karyawan pada tahap awal karir yang menunjukkan potensi dan kinerja baik, sehingga mendapatkan kenaikan gaji yang kompetitif sebagai bentuk apresiasi.

Cluster 1: Karyawan Senior & Stabil

Karakteristik: Memiliki pendapatan bulanan dan level jabatan tertinggi di antara semua segmen.

Interpretasi: Ini adalah para karyawan senior, manajer, atau eksekutif yang menjadi tulang punggung perusahaan. Mereka memiliki kompensasi yang sangat baik dan merupakan aset penting untuk dipertahankan.

Cluster 2: Karyawan Berisiko (At-Risk)

Karakteristik: Pendapatan bulanan, level jabatan, dan persentase kenaikan gaji semuanya berada pada level terendah.

Interpretasi: Karyawan di segmen ini adalah yang paling rentan untuk keluar. Mereka mungkin merasa kurang dihargai karena kompensasi dan pertumbuhan karir yang stagnan. Segmen ini memerlukan perhatian khusus dari manajemen.

🛠️ Teknologi yang Digunakan
Bahasa Pemrograman: Python

Library Analisis Data: Pandas, NumPy, Matplotlib, Seaborn

Library Machine Learning: Scikit-learn