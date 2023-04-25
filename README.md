#  Project Akhir Algoritma dan Struktur Data
#### Tema : Perpustakaan
###### Kelompok 13
---
### Deskripsi Program
Program ini dibuat dengan tujuan menawarkan kemudahan bagi pengguna untuk membuka akses seluas-luasnya terhadap informasi yang telah dipublikasikan. Selain itu program ini juga dapat memfasilitasi perkembangan secara sistematis dengan cara mengumpulkan, menyimpan, dan mengatur data atau informasi yang kemudian akan disajikan.
Program ini dibuat dengan menggunakan salah satu struktur data yaitu linked list, menggunakan algoritma merge sort untuk melakukan sorting dan menggunakan jump search untuk melakukan searching.
Prgram ini menggunakan database mysql pada registrasi dan login.

### Struktur Project

### Fitur dan Fungsionalitas
| Fitur | Fungsionalitas |
| ------ | ------ |
| Login admin | pintu masuk bagi admin untuk mengakses program. Login dimaksudkan untuk mengatur proses identifikasi. |
| Login pengunjung | pintu masuk bagi pengunjung untuk mengakses program.|
| Class linked Buku | kumpulan nodes yang merepresentasikan sebuah sequence. |
| Class admin | wadah menghimpun data admin dan kebergunaan yang kemudian menghasilkan objek |
| Class user | wadah menghimpun data pengunjung dan kebergunaan yang kemudian menghasilkan objek |
| Menu utama | bagian yang di dalamnya terdapat berbagai perintah yang digunakan untuk menjalankan fungsi tertentu pada sebuah program |
| Menu admin | sebuah strip horizontal yang berisi daftar menu yang tersedia untuk admin |
| Menu user | sebuah strip horizontal yang berisi daftar menu yang tersedia untuk pengunjung |

### Cara penggunaan
- Pertama tama user memilih pilihan yang ada pada menu utama, apakah user ingin login sebagai admin, login sebagai pengunjung atau ingin melakukan registrasi terlebih dahulu
- Jika user memilih login admin maka user akan dimintai untuk memasukkan username dan passwaord yang sudah ditentukan sebelumnya
- Jika user memilih login pengunjung maka user akan dimintai untuk memasukkan username dan juga password yang telah dbuat oleh user pada saat registrasi atau pembuatan akun
- Jika user memilih registrasi maka user akan  dimintai untuk membuat username dan password terlebih dahulu, jika username ternyata telah ada di dalam database, maka user akan dimintai untuk memasukkan username yang lain
- Sebagai admin, kita dapat melakukan beberapa hal seperti melihat, mencari, menambah dan menghapus data buku. Intinya admin dapat melakukan pengelolaan data pada setiap buku
- Sebagai pengunjung, kita dapat melihat, mencari, meminjam dan mengembalikan buku yang telah dipinjam
