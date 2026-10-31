# Hello UNIMED - Pertemuan 1 Pemrograman Mobile

## Identitas
- Nama  : Nayla Luthfiah Hanan
- NIM   : 4243250054
- Kelas : Ilmu Komputer D 2024

## Versi Flutter
<img width="590" height="102" alt="image" src="https://github.com/user-attachments/assets/cbcd943d-617e-48e5-9755-ef07e47caa1f" />


## Tangkapan layar
- flutter doctor: <img width="602" height="215" alt="image" src="https://github.com/user-attachments/assets/f7ea818f-ece2-4b7e-aad1-53e39101a8ec" />
- Aplikasi berjalan di emulator/perangkat Android: (gambar)

## Kendala dan solusi
1. Folder Flutter tidak bisa dipindah ("Folder In Use"), saya sudah menutup vscode, terminal vscode, dan pada bagian task manager juga ternyata masih belum bisa. Solusinya adalah saya restart laptop..
2. Emulator Android (Medium Phone API 37.0) langsung berhenti saat dijalankan dengan pesan "The emulator process for AVD has terminated", jadi `flutter devices` tidak menemukan perangkat Android. Saya mengecek penyebabnya, yaitu virtualisasi di BIOS, Windows Hypervisor Platform, dan versi system image yang masih sangat baru. (Tulis solusi yang akhirnya berhasil, misalnya: emulator baru dengan API 36 / memakai ponsel fisik dengan USB debugging.)
3. VS Code terbuka di folder `D:\dev`, bukan `D:\dev\hello_unimed`, sehingga file SDK Flutter ikut terbaca dan Problems mencapai ribuan. Solusinya menutup folder, lalu membuka langsung folder proyek dengan File > Open Folder.

## Penggunaan AI
Bagian yang dibantu AI mengenai pemindahan folder flutter mengingat penyimpanan dan folder user saya yang ada spasi, saya takut berpengaruh jadi saya pindahkan ke folder baru dan mengikuti langkah dari AI. Untuk bagian eror karena saya masih ada di folder besar dan saya salah masuk foldernya, jadi saya diminta untuk membuka folder tujuan langsung agar tidak bingung. Kemudian saya menggunakan AI untuk bertanya mengenai hal-hal yang saya bingung.

## Esai: Native, Hybrid, Cross-platform
Dalam pembuatan aplikasi mobile, ada tiga pendekatan yang bisa digunakan, yaitu native, hybrid, dan cross-platform. Ketiganya memiliki perbedaan dari segi cara pembuatan, performa, dan penggunaannya.
Native adalah pendekatan untuk membuat aplikasi khusus untuk satu sistem operasi. Contohnya, aplikasi Android bisa dibuat menggunakan Kotlin, sedangkan aplikasi iOS menggunakan Swift. Kelebihan native adalah performanya bagus dan bisa menggunakan fitur perangkat secara langsung. Contoh penggunaannya adalah aplikasi mobile banking yang membutuhkan keamanan tinggi dan fitur sidik jari untuk login.
Hybrid adalah pendekatan yang menggunakan teknologi web seperti HTML, CSS, dan JavaScript untuk membuat aplikasi mobile. Menurut saya, pendekatan ini cocok untuk aplikasi sederhana karena bisa menghemat waktu dan biaya pembuatan. Contohnya adalah aplikasi katalog produk yang menampilkan daftar barang, harga, dan informasi penjual.
Cross-platform adalah pendekatan yang memungkinkan pengembang membuat aplikasi untuk Android dan iOS menggunakan sebagian besar kode yang sama. Contohnya adalah aplikasi pencatatan hasil panen yang bisa digunakan oleh petani dengan perangkat Android maupun iOS. Salah satu framework yang bisa digunakan adalah Flutter.
Jadi, ketiga pendekatan tersebut bisa dipilih sesuai kebutuhan. Native cocok untuk aplikasi yang membutuhkan performa tinggi, hybrid cocok untuk aplikasi sederhana, sedangkan cross-platform cocok untuk membuat aplikasi di beberapa sistem operasi tanpa harus menulis seluruh kode dari awal.
