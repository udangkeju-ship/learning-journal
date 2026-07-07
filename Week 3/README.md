# Binary & Executable

## Deskripsi

Pada pembelajaran minggu ketiga, saya mempelajari konsep dasar **Binary** dan **Executable**, yang menjadi fondasi dalam Reverse Engineering. Materi ini membahas bagaimana sebuah program dibangun dari source code hingga menjadi file executable, struktur internal executable, format file pada berbagai sistem operasi, serta konsep endianness yang digunakan dalam penyimpanan data di memori.

---

## Tujuan Pembelajaran

Setelah mempelajari materi ini, saya diharapkan mampu:

- Memahami perbedaan antara Binary dan Executable.
- Menjelaskan proses pembentukan file executable.
- Mengenal berbagai format file executable pada sistem operasi.
- Memahami struktur internal sebuah executable.
- Menjelaskan konsep Endianness dalam penyimpanan data.
- Memahami hubungan Binary dan Executable dengan Reverse Engineering.

---

## Materi yang Dipelajari

### Binary dan Executable

Saya mempelajari bahwa **Binary** merupakan representasi data dalam bentuk angka 0 dan 1 yang dapat dipahami langsung oleh CPU. Dalam Reverse Engineering, binary merujuk pada machine code yang dieksekusi oleh prosesor.

Sementara itu, **Executable** adalah file hasil proses kompilasi yang memiliki format tertentu sehingga dapat dimuat oleh sistem operasi dan dijalankan sebagai sebuah program.

---

### Proses Pembentukan Executable

Saya mempelajari tahapan pembentukan sebuah executable, yaitu:

1. **Preprocessing** – Memproses direktif seperti `#include` dan `#define`.
2. **Compiling** – Mengubah source code menjadi bahasa Assembly.
3. **Assembling** – Mengubah Assembly menjadi object file.
4. **Linking** – Menggabungkan object file dan library menjadi satu file executable.

---

### Format File Executable

Saya mempelajari beberapa format executable yang digunakan oleh berbagai sistem operasi, antara lain:

- **Portable Executable (PE)** untuk Windows.
- **Executable and Linkable Format (ELF)** untuk Linux dan Unix.
- **Mach-O** untuk macOS dan iOS.

Saya juga memahami bahwa setiap format memiliki struktur header yang berbeda sebagai identitas file.

---

### Struktur Internal Executable

Saya mempelajari beberapa bagian penting dalam sebuah executable, yaitu:

- **Header** untuk menyimpan metadata file.
- **.text Section** yang berisi instruksi machine code.
- **.data Section** yang berisi data global atau statis.
- **.rsrc Section** yang berisi resource seperti ikon, gambar, maupun menu aplikasi.

---

### Endianness

Saya mempelajari bagaimana data disimpan di dalam memori melalui dua metode utama:

- **Little Endian**, yaitu byte dengan nilai paling rendah disimpan pada alamat memori terendah.
- **Big Endian**, yaitu byte dengan nilai paling tinggi disimpan pada alamat memori terendah.

Pemahaman mengenai endianness penting ketika membaca data hexadecimal maupun melakukan analisis binary.

---

### Keterkaitan dengan Reverse Engineering

Materi ini memberikan dasar untuk memahami bagaimana file executable dianalisis menggunakan berbagai tools Reverse Engineering, seperti:

- **Disassembler** untuk mengubah machine code menjadi Assembly.
- **Decompiler** untuk merekonstruksi kode tingkat tinggi.
- **Hex Editor** untuk melihat dan memodifikasi isi file dalam bentuk hexadecimal.

---

## Hasil Pembelajaran

Setelah mempelajari materi ini, saya dapat:

- Menjelaskan perbedaan Binary dan Executable.
- Memahami proses pembentukan executable dari source code.
- Mengenali format executable pada Windows, Linux, dan macOS.
- Memahami fungsi setiap bagian utama dalam struktur executable.
- Menjelaskan konsep Endianness dan penerapannya dalam analisis binary.
- Memahami dasar penggunaan Disassembler, Decompiler, dan Hex Editor dalam Reverse Engineering.

---

## Kesimpulan

Materi Binary dan Executable memberikan pemahaman mengenai bagaimana sebuah program dibangun, disimpan, dan dijalankan oleh sistem operasi. Selain itu, saya juga memahami struktur internal executable, format file pada berbagai platform, serta konsep endianness yang menjadi dasar dalam membaca machine code. Pengetahuan ini menjadi bekal penting sebelum mempelajari teknik analisis executable dan malware secara lebih mendalam menggunakan berbagai tools Reverse Engineering.
