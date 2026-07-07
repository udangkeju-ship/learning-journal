# Modern Computer System Architecture: Von Neumann, CPU, ISA, and Memory Management

## Deskripsi

Pada pembelajaran minggu kedua, saya mempelajari dasar-dasar arsitektur sistem komputer modern yang menjadi fondasi dalam Reverse Engineering. Materi ini membahas bagaimana komputer menjalankan sebuah program, mulai dari proses eksekusi instruksi oleh CPU, komunikasi dengan memori, hingga bagaimana perangkat lunak berinteraksi dengan perangkat keras melalui Instruction Set Architecture (ISA).

---

## Tujuan Pembelajaran

Setelah mempelajari materi ini, saya diharapkan mampu:

- Memahami konsep dasar arsitektur sistem komputer modern.
- Menjelaskan cara kerja arsitektur Von Neumann.
- Mengenal komponen utama CPU beserta fungsinya.
- Memahami Instruction Set Architecture (ISA).
- Menjelaskan konsep dasar manajemen memori.
- Menghubungkan konsep arsitektur komputer dengan Reverse Engineering.

---

## Materi yang Dipelajari

### Arsitektur Von Neumann

Saya mempelajari konsep **Stored Program Architecture**, yaitu instruksi program dan data disimpan pada memori yang sama. Saya juga memahami siklus kerja CPU yang terdiri dari:

- Fetch
- Decode
- Execute

Siklus ini menjelaskan bagaimana CPU mengambil instruksi dari memori, menerjemahkannya, kemudian mengeksekusinya.

---

### Central Processing Unit (CPU)

Saya mempelajari komponen utama CPU, di antaranya:

- **Arithmetic Logic Unit (ALU)** untuk melakukan operasi aritmatika dan logika.
- **Control Unit (CU)** untuk mengatur jalannya instruksi.
- **Register** sebagai penyimpanan data sementara yang berkecepatan tinggi.
- **Program Counter (PC)** untuk menyimpan alamat instruksi berikutnya.
- **Stack Pointer (SP)** untuk mengelola area stack.

---

### Instruction Set Architecture (ISA)

Saya mempelajari bahwa ISA merupakan penghubung antara perangkat lunak dan perangkat keras. Materi yang dipelajari meliputi:

- Pengertian ISA.
- Perbedaan ISA dan Microarchitecture.
- Arsitektur x86 dan x86-64.
- Jenis instruksi seperti:
  - Data Transfer
  - Arithmetic
  - Logical
  - Control Flow

---

### Manajemen Memori

Saya mempelajari bagaimana sistem operasi mengelola memori agar program dapat berjalan secara efisien. Konsep yang dipelajari meliputi:

- Virtual Memory
- Physical Memory
- Memory Addressing
- Stack
- Heap
- Segment Memori

---

### Keterkaitan dengan Reverse Engineering

Materi ini memberikan pemahaman dasar mengenai:

- Cara CPU mengeksekusi instruksi Assembly.
- Fungsi register saat proses debugging.
- Struktur memori program ketika dianalisis.
- Dasar membaca hasil disassembly pada tools Reverse Engineering.

---

## Hasil Pembelajaran

Setelah mempelajari materi ini, saya dapat:

- Menjelaskan cara kerja arsitektur Von Neumann.
- Memahami fungsi setiap komponen CPU.
- Menjelaskan peran ISA dalam komunikasi antara software dan hardware.
- Memahami organisasi memori pada sistem komputer modern.
- Menghubungkan konsep CPU dan memori dengan proses Reverse Engineering.

---

## Kesimpulan

Materi mengenai arsitektur sistem komputer modern memberikan dasar yang sangat penting sebelum mempelajari Reverse Engineering lebih lanjut. Dengan memahami bagaimana CPU bekerja, bagaimana instruksi dieksekusi, serta bagaimana memori dikelola oleh sistem operasi, saya memiliki bekal yang lebih kuat untuk mempelajari assembly, debugging, analisis executable, dan malware analysis pada materi berikutnya.
