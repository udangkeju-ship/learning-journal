# Modern Computer System Architecture: Von Neumann, CPU, ISA, and Memory Management

Repository ini berisi ringkasan materi dan hasil pembelajaran mengenai **Arsitektur Sistem Komputer Modern** sebagai dasar untuk memahami cara kerja komputer dalam konteks Reverse Engineering. Materi mencakup arsitektur Von Neumann, komponen CPU, Instruction Set Architecture (ISA), serta konsep manajemen memori yang menjadi fondasi dalam analisis perangkat lunak.

---

## Deskripsi

Pada pembelajaran minggu kedua, saya mempelajari bagaimana sebuah komputer modern menjalankan instruksi mulai dari proses pengambilan instruksi dari memori, pemrosesan oleh CPU, hingga penyimpanan hasilnya kembali ke memori. Pemahaman mengenai arsitektur komputer sangat penting dalam Reverse Engineering karena membantu memahami bagaimana program dieksekusi pada tingkat rendah.

---

## Tujuan

Repository ini dibuat dengan tujuan untuk:

- Memahami konsep dasar arsitektur sistem komputer modern.
- Mempelajari cara kerja arsitektur Von Neumann.
- Mengenal struktur dan fungsi komponen utama CPU.
- Memahami Instruction Set Architecture (ISA) sebagai antarmuka antara perangkat keras dan perangkat lunak.
- Mempelajari konsep dasar manajemen memori yang digunakan sistem operasi.
- Menjadi dasar sebelum mempelajari Assembly, Disassembly, dan Reverse Engineering.

---

## Materi yang Dipelajari

### 1. Arsitektur Von Neumann
- Konsep stored-program.
- Siklus Fetch–Decode–Execute.
- Hubungan antara CPU, memori, dan perangkat I/O.

### 2. Central Processing Unit (CPU)
- Arithmetic Logic Unit (ALU).
- Control Unit (CU).
- Register.
- Program Counter (PC).
- Stack Pointer (SP).

### 3. Instruction Set Architecture (ISA)
- Pengertian ISA.
- Perbedaan ISA dan Microarchitecture.
- Arsitektur x86 dan x86-64.
- Jenis instruksi dasar (Data Transfer, Arithmetic, Logic, Control Flow).

### 4. Manajemen Memori
- Virtual Memory.
- Physical Memory.
- Memory Addressing.
- Stack.
- Heap.
- Segment Memori.

### 5. Hubungan dengan Reverse Engineering
- Cara CPU mengeksekusi instruksi Assembly.
- Pentingnya register dalam proses debugging.
- Pemahaman layout memori saat melakukan analisis program.
- Dasar membaca kode Assembly menggunakan tools Reverse Engineering.

---

## Tools yang Dikenal

- Ghidra
- IDA Free / IDA Pro
- x64dbg
- Process Hacker
- PE-bear

---

## Struktur Repository

```text
Week 2/
│
├── README.md
├── materi/
│   └── Architecture_System_Computer.pdf
│
├── notes/
│   └── summary.md
│
└── assets/
    ├── images/
    └── screenshots/
```

---

## Hasil Pembelajaran

Setelah mempelajari materi ini, saya mampu:

- Menjelaskan cara kerja arsitektur Von Neumann.
- Memahami fungsi setiap komponen utama CPU.
- Menjelaskan konsep Instruction Set Architecture (ISA).
- Memahami bagaimana memori diorganisasi oleh sistem operasi.
- Menghubungkan konsep CPU dan memori dengan proses Reverse Engineering.
- Memiliki dasar yang lebih kuat sebelum mempelajari Assembly dan analisis executable.

---

## Kesimpulan

Materi mengenai arsitektur sistem komputer modern memberikan fondasi penting dalam Reverse Engineering. Dengan memahami bagaimana CPU mengeksekusi instruksi, bagaimana ISA mendefinisikan bahasa mesin, serta bagaimana memori dikelola oleh sistem operasi, proses analisis program pada level rendah menjadi lebih mudah dipahami. Pengetahuan ini menjadi dasar untuk mempelajari disassembly, debugging, dan analisis malware pada pertemuan berikutnya.
