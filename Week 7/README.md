# Dynamic Analysis Malware

## Deskripsi

Pada pembelajaran minggu ketujuh, saya mempelajari **Dynamic Analysis Malware**, yaitu metode analisis malware dengan menjalankan file pada lingkungan yang aman untuk mengamati perilakunya secara langsung. Analisis ini bertujuan untuk mengetahui aktivitas malware saat dieksekusi, seperti perubahan pada sistem, komunikasi jaringan, pembuatan proses, hingga modifikasi registry atau file.

---

## Tujuan Pembelajaran

Setelah mempelajari materi ini, saya diharapkan mampu:

- Memahami konsep dasar Dynamic Analysis Malware.
- Mengenal tahapan analisis malware dengan menjalankan file pada lingkungan yang aman.
- Menggunakan tools untuk mengamati perilaku malware selama proses eksekusi.

---

## Materi yang Dipelajari

### Pengertian Dynamic Analysis

Saya mempelajari bahwa **Dynamic Analysis** merupakan metode analisis malware dengan cara menjalankan file pada lingkungan yang terisolasi, seperti Virtual Machine atau Sandbox. Tujuannya adalah untuk mengamati perilaku malware secara langsung tanpa membahayakan sistem utama.

---

### Perilaku Malware yang Dianalisis

Selama proses Dynamic Analysis, saya mempelajari beberapa aktivitas yang dapat diamati, antara lain:

- Pembuatan atau penghentian proses (Process Activity).
- Perubahan file pada sistem.
- Modifikasi Windows Registry.
- Komunikasi jaringan (Network Activity).
- Pembuatan service atau persistence.
- Aktivitas Command and Control (C2) jika ada.

Informasi tersebut membantu memahami bagaimana malware bekerja setelah dijalankan.

---

### Tools Dynamic Analysis

Saya mengenal beberapa tools yang umum digunakan dalam Dynamic Analysis, di antaranya:

- Process Hacker
- Process Monitor (Procmon)
- Wireshark
- TCPView
- Regshot
- x64dbg
- CAPE Sandbox

Masing-masing tools digunakan untuk memantau aktivitas proses, registry, jaringan, maupun perilaku malware secara keseluruhan.

---

### Keunggulan Dynamic Analysis

Saya mempelajari beberapa kelebihan Dynamic Analysis, yaitu:

- Dapat mengamati perilaku malware secara langsung.
- Mampu mendeteksi aktivitas yang tidak terlihat pada Static Analysis.
- Membantu menemukan indikator kompromi (IoC).
- Memberikan gambaran mengenai dampak malware terhadap sistem.

---

### Keterbatasan Dynamic Analysis

Selain kelebihannya, Dynamic Analysis juga memiliki beberapa keterbatasan, seperti:

- Membutuhkan lingkungan analisis yang aman.
- Berisiko menginfeksi sistem jika dilakukan tanpa isolasi.
- Beberapa malware memiliki teknik Anti-Debugging atau Anti-Virtual Machine sehingga dapat menghindari proses analisis.

---

## Hasil Pembelajaran

Setelah mempelajari materi ini, saya dapat:

- Memahami konsep dan tahapan dasar Dynamic Analysis Malware.
- Mengamati perilaku malware menggunakan berbagai tools analisis.
- Menjelaskan kelebihan dan keterbatasan Dynamic Analysis dalam proses malware analysis.

---

## Kesimpulan

Materi **Dynamic Analysis Malware** memberikan pemahaman mengenai teknik analisis malware dengan mengamati perilakunya saat dijalankan. Dengan menggunakan lingkungan yang aman dan berbagai tools monitoring, saya dapat memahami aktivitas malware secara lebih mendalam serta memperoleh informasi yang tidak dapat diperoleh melalui Static Analysis. Kedua metode tersebut saling melengkapi dalam proses Malware Analysis.
