#  Project Akhir Algoritma dan Struktur Data
#### Tema : Perpustakaan
###### Kelompok 13
---
### Deskripsi Program
Program ini dibuat dengan tujuan menawarkan kemudahan bagi pengguna untuk membuka akses seluas-luasnya terhadap informasi yang telah dipublikasikan. Selain itu program ini juga dapat memfasilitasi perkembangan secara sistematis dengan cara mengumpulkan, menyimpan, dan mengatur data atau informasi yang kemudian akan disajikan.
Program ini dibuat dengan menggunakan salah satu struktur data yaitu linked list, menggunakan algoritma merge sort untuk melakukan sorting dan menggunakan jump search untuk melakukan searching.
Prgram ini menggunakan database mysql pada registrasi dan login.

### Struktur Project
1. Menu utama
    Menu utama ini berisi opsi yang dapat dipilih oleh user untuk kemudian diekseskusi oleh program sesuai dengan pilihan yang telah dipilih oleh user.
2. Login admin
    Login admin merupakan suatu proses untuk masuk ke dalam menu admin, yang dimana user akan dimintai untuk memasukkan username dan juga password yang telah ditentukan sebelumnya.
3. Login pengunjung
    Login pengunjung merupakan suatu proses untuk masuk ke dalam menu pengunjung, yang dimana user akan dimintai untuk memasukkan username dan juga password yang telah dibuat sebelumnya pada saat melakukan registrasi pengunjung. 
4. Registrasi pengunjung
    Registrasi pengunjung ini hanya dapat dilakukan oleh user yang belum memliki akun sebelumnya karena username dan juga password dibutuhkan sebagai pintu masuk ke dalam program. User yang melakukan registrasi akan otomatis memiliki role sebagai pengunjung, bukan admin.
5. Menu admin
    Menu admin ini berisi opsi yang dapat dipilih oleh admin seperti melihat, mencari, menambahkan, dan menghapus buku, juga dapat melihat dan menghapus anggota perpustakaan, melihat antrean perpustakaan dan melihat riwayat list peminjaman buku. Previlage yang dimiliki oleh admin tentu berbeda dengan yang dimiki oleh pengunjung. Opsi yang dapat dipilih oleh user tidak sebanyak dengan opsi yang dapat dipilih oleh admin.
6. Menu pengunjung
    Menu ini berisi opsi yang dapat dipilih oleh pengunjung seperti melihat, mencari, meminjam, dan mengembalikan buku, juga dapat menampilkan daftar bacaan.
    Pengunjung tidak dapat melakukan tata kelola data buku yang ada di perpustakaan karena hal ini hanya dapat dilakukan oleh admin.
### Fitur dan Fungsionalitas
| Fitur | Fungsionalitas |
| ------ | ------ |
| Login/Register | pintu masuk bagi admin ataupun pengunjung untuk mengakses program. Login atau registrasi dimaksudkan untuk mengatur proses identifikasi. |
| Lihat buku | menampilkan informasi/data dari buku-buku yang ada di perpustakaan. Informasi tersebut dapat berupa judul, pengarang, penerbit, genre, tahun terbit, dan juga status. Status disini diperuntukkan untuk memberi informasi mengenai ketersediaan buku yang akan dpinjam, apakah buku tersebut sedang dalam kondisi dipinjam oleh pengunjung yang lain atau tidak. | 
| Cari buku | membantu memudahkan user untuk menemukan data/informasi dari buku yang ingin dicari. |
| Tambah buku | menambahkan data buku ke dalam  perpustakaan yang kemudian akan ditampilkan kepada user sehingga dapat menambah pilihan buku yang dapat dipinjam oleh pengunjung. |
| Hapus buku | menghapus atau menghilangkan data buku yang mungkin sudah tidak dapat lagi disajikan atau dipinjamkan kepada pengunjung. |
| Lihat anggota | menampilkan daftar anggota yang telah terdaftar di dalam perpustakaan |
| Hapus anggota | menghapus pengunjung dari daftar keanggotaan di dalam perpustakaan |
| Lihat antrean | menampilkan daftar antrean pengunjung yang akan meminjam buku. Peminjaman buku hanya dapat dilakukan jika admin memberikan persetujuan kepada pengunjung untuk melakukan peminjaman atas buku yang ada di dalam perpustakaan |
| Lihat riwayat | menampilkan daftar riwayat peminjaman buku yang dilakukan oleh pengunjung di dalam perpustakaan |
| Pinjam buku | menambahkan buku ke dalam daftar antrean untuk kemudian dilakukan persetujuan oleh admin sebelum buku dapat dipinjam oleh pengunjung |
| Kembalikan buku | mengubah status buku dari yang sebelumnya unavailable menjadi available yang berarti buku tersebut sudah dapat dipinjam oleh pengunjung yang lain. |
| Lihat daftar bacaan | menampilkan daftar riwayat buku yang telah dipinjam oleh pengunjung selama menjadi anggota perpustakaan |

### Cara penggunaan
- Pertama tama user memilih pilihan yang ada pada menu utama, apakah user ingin login sebagai admin, login sebagai pengunjung atau ingin melakukan registrasi terlebih dahulu
- Jika user memilih login admin maka user akan dimintai untuk memasukkan username dan passwaord yang sudah ditentukan sebelumnya
- Jika user memilih login pengunjung maka user akan dimintai untuk memasukkan username dan juga password yang telah dbuat oleh user pada saat registrasi atau pembuatan akun
- Jika user memilih registrasi maka user akan  dimintai untuk membuat username dan password terlebih dahulu, jika username ternyata telah ada di dalam database, maka user akan dimintai untuk memasukkan username yang lain
- Sebagai admin, kita dapat melakukan beberapa hal seperti melihat, mencari, menambah dan menghapus data buku. Intinya admin dapat melakukan pengelolaan data pada setiap buku
- Sebagai pengunjung, kita dapat melihat, mencari, meminjam dan mengembalikan buku yang telah dipinjam
