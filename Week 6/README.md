# Static Analysis Malware

## Deskripsi

Pada pembelajaran minggu keenam, saya mempelajari **Static Analysis Malware**, yaitu metode analisis malware tanpa menjalankan file tersebut. Analisis dilakukan dengan mengamati struktur, metadata, string, header, section, import function, serta karakteristik lain yang terdapat pada file executable. Metode ini bertujuan untuk memperoleh informasi awal mengenai malware secara aman sebelum dilakukan analisis lebih lanjut.

---

## Tujuan Pembelajaran

Setelah mempelajari materi ini, saya diharapkan mampu:

- Memahami konsep dasar Static Analysis Malware.
- Mengenal tahapan analisis malware tanpa menjalankan file.
- Menggunakan berbagai tools untuk memperoleh informasi dari file executable.

---

## Materi yang Dipelajari

### Pengertian Static Analysis

Saya mempelajari bahwa **Static Analysis** merupakan metode analisis malware yang dilakukan tanpa mengeksekusi file. Pendekatan ini digunakan untuk memahami karakteristik malware melalui pemeriksaan struktur file dan informasi yang terkandung di dalamnya.

---

### Informasi yang Dianalisis

Pada proses Static Analysis, saya mempelajari beberapa informasi penting yang dapat diperoleh, antara lain:

- File Header
- File Hash (MD5, SHA-1, SHA-256)
- Strings
- PE Header
- Section
- Import dan Export Function
- Compiler atau Packer yang digunakan

Informasi tersebut membantu dalam mengidentifikasi karakteristik dan perilaku awal suatu malware.

---

### Tools Static Analysis

Saya mengenal beberapa tools yang umum digunakan dalam Static Analysis, di antaranya:

- Detect It Easy (DIE)
- Ghidra
- IDA Free / IDA Pro
- HxD (Hex Editor)
- Strings

Setiap tools memiliki fungsi yang berbeda, mulai dari identifikasi file, analisis struktur executable, hingga proses disassembly.

---

### Keunggulan Static Analysis

Saya mempelajari beberapa kelebihan Static Analysis, yaitu:

- Tidak perlu menjalankan malware.
- Risiko infeksi terhadap sistem lebih rendah.
- Dapat memperoleh informasi awal mengenai malware dengan cepat.
- Cocok digunakan sebagai tahap awal sebelum Dynamic Analysis.

---

### Keterbatasan Static Analysis

Selain kelebihannya, Static Analysis juga memiliki beberapa keterbatasan, seperti:

- Sulit menganalisis malware yang menggunakan packer atau obfuscation.
- Tidak dapat mengamati perilaku malware saat dijalankan.
- Beberapa informasi baru dapat diketahui melalui Dynamic Analysis.

---

## Hasil Pembelajaran

Setelah mempelajari materi ini, saya dapat:

- Memahami konsep dan tahapan dasar Static Analysis Malware.
- Mengidentifikasi informasi penting pada file executable menggunakan berbagai tools.
- Menjelaskan kelebihan dan keterbatasan Static Analysis dalam proses analisis malware.

---

## Kesimpulan

Materi **Static Analysis Malware** memberikan pemahaman mengenai teknik analisis malware tanpa menjalankan file. Dengan memanfaatkan berbagai tools dan melakukan pemeriksaan terhadap struktur executable, saya dapat memperoleh informasi penting sebagai dasar untuk memahami karakteristik malware sebelum melanjutkan ke tahap **Dynamic Analysis**.
