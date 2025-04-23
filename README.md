# Firman_2306107_Sistem-Pakar-Certainty-Factor-Fuzzy-Logic-

# Tugas-CF-Fuzzy_Logic

**Certainty Factor** merupakan pendekatan yang digunakan untuk menangani ketidakpastian dalam sistem pakar. CF menilai tingkat kepercayaan seorang pakar terhadap suatu kesimpulan berdasarkan gejala yang diberikan.  
- Nilai CF berada dalam rentang -1 hingga +1:  
  - +1 menunjukkan keyakinan penuh atau netral  
  - -1 menunjukkan keyakinan penuh bahwa informasi tersebut salah  

CF mengombinasikan beberapa gejala dengan tingkat kepercayaan yang berbeda-beda, lalu menghasilkan diagnosis akhir secara proporsional. Rumus kombinasi CF yang digunakan:  
                      CFgabungan = CF1 + CF2.(1 - CF1)  
Dalam studi kasus yang kamu kerjakan, sistem pakar berhasil menyimpulkan diagnosis flu berdasarkan input gejala dan memberikan output berupa nilai keyakinan numerik (contohnya 0.97).

**Fuzzy Logic** adalah pendekatan logika yang digunakan untuk menangani data yang tidak pasti atau ambigu. Berbeda dari logika biner (0 atau 1), fuzzy logic memakai derajat keanggotaan antara 0 sampai 1.  
Sangat cocok untuk kondisi seperti "suhu tinggi", "lembab", atau "sedang", yang tidak bisa diklasifikasikan secara pasti.  
Komponen utamanya meliputi:  
- **Fuzzy set**: himpunan tak tegas  
- **Membership function**: fungsi untuk menentukan tingkat keanggotaan (contoh: suhu 28°C bisa 0.6 "nyaman", 0.4 "panas")  
- **Fuzzification**: proses mengubah nilai numerik ke bentuk fuzzy  
- **Inference (aturan IF-THEN)**: proses logika fuzzy  
- **Defuzzification**: konversi dari hasil fuzzy ke bentuk numerik (contohnya: kipas 66%)  

Dalam studi kasus kamu (pengaturan kipas AC), sistem mampu menentukan kecepatan kipas berdasarkan suhu dan kelembaban dengan menggunakan aturan fuzzy yang telah kamu rancang sendiri.
