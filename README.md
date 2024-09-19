# Gradle Task Project

Proyek Gradle sederhana dengan tugas custom bernama `greetingTask`

## Tugas

Tugas custom `greetingTask` mencetak pesan ucapan berdasarkan parameter yang diterima dari command line

- Jika parameter `nama` diberikan, tugas ini akan mencetak pesan ucapan dengan nama yang dipersonalisasi
- Jika parameter `nama` tidak diberikan, tugas ini akan mencetak pesan default "Gradle User"

## Dependensi

Proyek ini menggunakan pustaka:
- **Guava**: Koleksi utilitas dan pustaka tambahan dari Google
- **JUnit**: Digunakan untuk unit testing

## Cara Menjalankan

Untuk menjalankan tugas `greetingTask`, gunakan perintah berikut di terminal:

- Dengan parameter `nama`:
  ```bash
  gradlew.bat greetingTask -Pnama=YourName

## Tujuan

- Membuat tugas custom di Gradle yang menampilkan pesan ucapan berdasarkan nama
- Menambahkan pustaka eksternal seperti Guava dan JUnit untuk digunakan dalam proyek
- Menggunakan Git untuk menyimpan dan melacak perubahan kode, serta mengunggah proyek ke GitHub agar bisa diakses dan dibagikan
