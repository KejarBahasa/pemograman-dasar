---
sidebar_position: 4
---

# Interpreter & Compiler

## Interpreter

Interpreter adalah program komputer yang mengeksekusi kode sumber bahasa pemrograman tingkat tinggi secara langsung, tanpa perlu menerjemahkannya menjadi bahasa mesin terlebih dahulu.

- **Proses Eksekusi**
  Interpreter membaca kode sumber baris demi baris, menganalisis, dan menjalankan instruksi secara langsung. Jika ada kesalahan pada suatu baris, interpreter akan menghentikan eksekusi dan memberikan pesan error.

- **Kecepatan Eksekusi**
  Program yang dijalankan oleh interpreter biasanya lebih lambat dibandingkan dengan program yang dikompilasi, karena setiap baris kode perlu dianalisis dan dijalankan secara berulang.

### Siklus Pengembangan Menggunakan Interpreter

- **Menulis Kode Sumber**
  Programmer menulis program dalam bahasa pemrograman tingkat tinggi, misalnya Python atau JavaScript.

- **Eksekusi Langsung**
  Kode sumber dijalankan langsung oleh interpreter. Jika terdapat kesalahan sintaks atau runtime error, eksekusi akan dihentikan, dan interpreter akan menampilkan pesan error yang sesuai.

- **Iterasi**
  Programmer dapat segera memperbaiki kesalahan dan menjalankan kembali program, yang membuat interpreter sangat cocok untuk pengembangan dan eksperimen cepat.

## Compiler

Compiler adalah program komputer yang menerjemahkan kode sumber yang ditulis dalam bahasa pemrograman tingkat tinggi (seperti C, C++, atau Pascal) menjadi bahasa mesin yang dapat dieksekusi langsung oleh komputer.

- **Proses Kompilasi**
  Compiler mengambil seluruh kode sumber dan menerjemahkannya sekaligus menjadi file yang dapat dieksekusi. Proses ini disebut kompilasi.

- **Hasil Kompilasi**
  Setelah proses kompilasi selesai, compiler menghasilkan file output yang biasanya berekstensi .exe di Windows atau tanpa ekstensi di Unix/Linux (tergantung pada bahasa dan platform).

- **Kecepatan Eksekusi**
  Program yang telah dikompilasi biasanya berjalan lebih cepat dibandingkan dengan program yang dijalankan melalui interpreter karena kode mesin yang dihasilkan sudah siap dijalankan tanpa perlu interpretasi tambahan.

### Siklus Pengembangan Menggunakan Compiler

- **Menulis Kode Sumber**
  Programmer menulis program dalam bahasa pemrograman tingkat tinggi, misalnya Pascal atau C.

- **Kompilasi**
  Kode sumber dikompilasi oleh compiler. Jika terdapat kesalahan sintaks atau error lain, proses kompilasi akan gagal, dan programmer harus memperbaiki kode sumbernya.

- **Eksekusi**
  Setelah kompilasi berhasil, file eksekusi yang dihasilkan dapat dijalankan langsung oleh komputer.

## Perbedaan antara Interpreter dan Compiler

#### Interpreter

- Menjalankan kode sumber secara langsung baris per baris.
- Tidak menghasilkan file eksekusi terpisah.
- Memudahkan debugging karena eksekusi berhenti pada baris yang salah.
- Digunakan oleh bahasa pemrograman seperti Python, JavaScript, Ruby, dan PHP.

#### Compiler

- Menerjemahkan seluruh kode sumber menjadi file eksekusi dalam satu langkah.
- Menghasilkan file eksekusi terpisah yang dapat dijalankan langsung oleh mesin.
- Lebih cepat dalam eksekusi karena kode mesin sudah dioptimalkan sebelumnya.
- Digunakan oleh bahasa pemrograman seperti C, C++, dan Pascal.
