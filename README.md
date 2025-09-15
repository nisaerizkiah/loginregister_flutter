#Praktikum Login-Register Flutter
Pada praktikum ini membuat aplikasi flutter sederhana yang memiliki fitur lagin dan register. Hasil akhirnya nanti menampilkan halaman login, halaman registrasi, dan halaman home setelah berhasil login.

Langkah Pengerjaan:
1. Tentukan struktur di dalam folder lib: ada folder bernama data, di dalamnya terdapat file user_data.dart
   kemudian ada file main.dart, login_page.dart, register_page.dart dan home_page.dart
2. File main.dart menjadi titik masuk aplikasi.
3. File user_data.dart untuk mebuat data sementara.
4. File register_page.dart halaman ini dipakai untuk menambahkan akun baru.
5. File login_page.dart halaman ini merupakan pintu masuk utama aplikasi.
6. File home_page.dart halaman ini akan tampil setelah user berhasil login.
7. Dibagian pubspec.yml tambahkan dependency google_fonts: ^6.2.1, karena applikasi tidak hanya menggunakan font bawaan Flutter, tapi mengatur teks supaya menggunakan font dari Google Fonts.
8. Kemudian setelah semua file selesai dibuat, jalankan perintah flutter run pada terminal, nanti akan otomatis masuk ke chrome untuk menampilkan hasilnya.
9. Maka tampilan hasilnya akan menampilkan halamn login:
<img width="1920" height="1200" alt="hasil1" src="https://github.com/user-attachments/assets/42cce9a5-c989-4c92-a87d-d4cf4a0eb57b" />

10. Jika user menekan Sign Up, maka diarahkan ke halaman Registrasi, kemudian inputkan fullname, email dan password:
<img width="1920" height="1200" alt="hasil2" src="https://github.com/user-attachments/assets/c6f95b7f-1562-4000-b9cd-d622d276e504" />

11. Setelah akun berhasil dibuat, user bisa login dengan akun barunya.
<img width="1920" height="1200" alt="hasil5" src="https://github.com/user-attachments/assets/eb229224-166e-4f31-ad30-59ff60fe4c6c" />

13. Jika sudah berhasil login, muncul halaman Home dengan sapaan nama.
<img width="1920" height="1200" alt="hasil6" src="https://github.com/user-attachments/assets/08f1760f-a1ca-46d8-9719-b665d3a0fd8b" />

15. Tombol Logout pojok kanan atas akan membawa user kembali ke halaman login nantinya.

