# Perbandingan Static Analysis dan Dynamic Analysis

## Deskripsi

Pada pembelajaran minggu kedelapan, saya mempelajari perbedaan antara **Static Analysis** dan **Dynamic Analysis** dalam proses malware analysis. Kedua metode memiliki tujuan yang sama, yaitu memahami karakteristik dan perilaku malware, namun dilakukan dengan pendekatan yang berbeda. Materi ini membantu saya memahami kapan masing-masing metode digunakan serta kelebihan dan keterbatasannya.

---

## Tujuan Pembelajaran

Setelah mempelajari materi ini, saya diharapkan mampu:

- Memahami perbedaan antara Static Analysis dan Dynamic Analysis.
- Mengetahui kelebihan dan keterbatasan dari masing-masing metode.
- Memilih metode analisis yang sesuai berdasarkan kebutuhan analisis malware.

---

## Materi yang Dipelajari

### Static Analysis

Static Analysis merupakan metode analisis malware tanpa menjalankan file. Analisis dilakukan dengan memeriksa struktur file, header, strings, import function, section, serta informasi lain yang terdapat pada file executable.

Karakteristik Static Analysis:

- Tidak menjalankan malware.
- Risiko terhadap sistem lebih rendah.
- Digunakan untuk memperoleh informasi awal mengenai malware.
- Cocok sebagai tahap awal dalam proses malware analysis.

---

### Dynamic Analysis

Dynamic Analysis merupakan metode analisis malware dengan menjalankan file pada lingkungan yang aman, seperti Virtual Machine atau Sandbox. Analisis dilakukan dengan mengamati perilaku malware selama proses eksekusi.

Karakteristik Dynamic Analysis:

- Menjalankan malware dalam lingkungan terisolasi.
- Mengamati aktivitas proses, file, registry, dan jaringan.
- Memberikan informasi mengenai perilaku malware secara langsung.
- Digunakan untuk melengkapi hasil Static Analysis.

---

### Perbandingan Static Analysis dan Dynamic Analysis

| Static Analysis | Dynamic Analysis |
|-----------------|------------------|
| Tidak menjalankan malware | Menjalankan malware di lingkungan aman |
| Risiko infeksi lebih rendah | Memiliki risiko jika lingkungan tidak terisolasi |
| Menganalisis struktur file | Menganalisis perilaku malware |
| Cepat memperoleh informasi awal | Memberikan informasi perilaku secara lebih lengkap |
| Sulit menganalisis malware yang di-obfuscate | Dapat mengamati perilaku malware secara langsung |

---

### Hubungan Kedua Metode

Saya mempelajari bahwa Static Analysis dan Dynamic Analysis bukanlah metode yang saling menggantikan, melainkan saling melengkapi. Static Analysis digunakan untuk memperoleh informasi awal mengenai malware, sedangkan Dynamic Analysis digunakan untuk mengamati perilaku malware saat dijalankan sehingga menghasilkan analisis yang lebih komprehensif.

---

## Hasil Pembelajaran

Setelah mempelajari materi ini, saya dapat:

- Menjelaskan perbedaan antara Static Analysis dan Dynamic Analysis.
- Memahami kelebihan serta keterbatasan masing-masing metode analisis.
- Menentukan metode analisis yang sesuai berdasarkan tujuan malware analysis.

---

## Kesimpulan

Materi **Perbandingan Static Analysis dan Dynamic Analysis** memberikan pemahaman bahwa kedua metode memiliki peran yang berbeda namun saling melengkapi dalam proses malware analysis. Dengan menggabungkan hasil dari Static Analysis dan Dynamic Analysis, proses analisis malware dapat dilakukan secara lebih menyeluruh sehingga menghasilkan informasi yang lebih akurat mengenai karakteristik maupun perilaku malware.
