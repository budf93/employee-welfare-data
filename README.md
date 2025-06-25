Analisis Data Karyawan Perusahaan (Proyek Akhir)

Latar Belakang

Proyek ini merupakan analisis data eksplorasi (EDA) terhadap data karyawan sebuah perusahaan. Tujuannya adalah untuk menemukan wawasan (insights) penting terkait faktor-faktor yang memengaruhi aspek-aspek kunci karyawan, seperti kompensasi, kinerja, dan karakteristik demografis. Analisis ini dilakukan oleh kelompok mahasiswa sebagai bagian dari proyek akhir mereka.

Tim Penyusun 

Fikri Budianto (2206025306)

Khansa Mahira (2206819413)

Dian Fathur Rahman (2206082096)

Gilang Fajar Pratama (2206082631)

Wawasan Utama (Key Insights)

Berdasarkan analisis data yang telah dilakukan, ditemukan tiga wawasan utama:

1. Hubungan Gaji dengan Frekuensi Perjalanan Bisnis
Pertanyaan: Apakah karyawan yang jarang melakukan perjalanan bisnis mendapatkan gaji lebih tinggi?

Temuan: Ya, karyawan dengan kategori perjalanan "Travel_Rarely" dan "Non-Travel" cenderung memiliki gaji bulanan (baik median maupun rata-rata) yang lebih tinggi dibandingkan dengan karyawan yang sering melakukan perjalanan bisnis ("Travel_Frequently").

Implikasi: Hal ini bisa mengindikasikan bahwa posisi yang lebih senior, strategis, atau teknis yang tidak memerlukan mobilitas tinggi mungkin mendapatkan kompensasi yang lebih besar. Sebaliknya, peran yang membutuhkan perjalanan sering mungkin berada di level operasional atau penjualan lapangan.

2. Pengaruh Lembur terhadap Kinerja Karyawan
Pertanyaan: Apakah karyawan yang bekerja lembur (overtime) memiliki kinerja yang lebih baik?

Temuan: Tidak secara langsung. Analisis menunjukkan bahwa kelompok yang tidak bekerja lembur justru memiliki persentase kinerja "Excellent" yang lebih tinggi (92.8%) dibandingkan kelompok yang lembur (81.1%). Namun, untuk kinerja tertinggi ("Outstanding"), kelompok yang bekerja lembur memiliki persentase yang lebih tinggi (17.2%) dibandingkan yang tidak (5.1%).

Implikasi: Bekerja lembur tidak menjamin kinerja yang lebih baik secara keseluruhan dan bahkan bisa berkorelasi dengan kinerja yang sedikit lebih rendah di kategori "Excellent". Namun, lembur mungkin terkait dengan proyek atau tugas mendesak yang hasilnya bisa dinilai "Outstanding".

3. Ciri-Ciri Karyawan dengan Pendapatan Tinggi
Pertanyaan: Apa saja karakteristik yang menonjol dari karyawan dengan pendapatan tinggi (didefinisikan sebagai kuartil teratas)?

Temuan: Karyawan dengan pendapatan tinggi (di atas ~$15,786 per bulan dalam dataset ini) menunjukkan beberapa ciri khas yang membedakan mereka:

Tingkat Jabatan (Job Level): Memiliki JobLevel yang secara signifikan lebih tinggi. Ini adalah prediktor terkuat.

Pengalaman Kerja (Total Working Years): Cenderung memiliki total masa kerja yang lebih lama.

Masa Kerja di Perusahaan (Years At Company): Telah mengabdi lebih lama di perusahaan saat ini.

Usia (Age): Rata-rata usia mereka sedikit lebih tinggi, yang sejalan dengan pengalaman kerja yang lebih banyak.

Kenaikan Gaji (Percent Salary Hike): Menariknya, persentase kenaikan gaji tahunan mereka rata-rata sedikit lebih tinggi (15.4%) dibandingkan kelompok lain (14.8%), yang mungkin mencerminkan penghargaan atas kinerja dan nilai strategis mereka.

Kesimpulan

Analisis ini memberikan beberapa wawasan kunci bagi manajemen sumber daya manusia. Faktor-faktor seperti tingkat jabatan, pengalaman, dan frekuensi perjalanan bisnis memiliki korelasi kuat dengan tingkat pendapatan. Selain itu, kebijakan terkait lembur mungkin perlu ditinjau untuk memastikan efektivitasnya terhadap kinerja karyawan secara keseluruhan.