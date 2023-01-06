# Project UAS Bahasa Pemrograman

Nama    :   Ghufron Malik</br>
NIM     :   312210559</br>
Kelas   :   TI.22.B2</br>


| NO |      DAFTAR ISI      |   LINK    |
|----|----------------------|-----------|
| 1  |Link YouTube          |[Click]|
| 2  |Daftar Nilai          |[Click]|
| 3  |Input Nilai           |[Click]|
| 4  |View Nilai            |[Click]|
| 5  |main.py               |[Click]|

# Ketentuan Program
![img1](image/satu.png)


# 1. DAFTAR NILAI

Untuk membuat file `daftar_nilai.py` kita harus membuat package yang berisi file seperti dalam ketentuan di atas terlebih dahulu.
### A. Source Code
Berikut adalah Source Code dari program di atas
![img2](image/daftar_nilai.png)

### B. Penjelasan
- `data = {}`. adalah Dictonary kosong. Fungsinya untuk menginput data dalam program tersebut dan memudahkan kita untuk memanggil data itu lagi.
- sedangkan `def` merupakan keyword yang digunakan untuk menyatakn suatu fungsi pada program. isi modul dengan beberapa fungsi yaitu `tambah_data`, `ubah_data`, `hapus_data`, dan `cari_data`.

# 2. INPUT NILAI

Selanjutnya membuat module `input_nilai.py` pada package view yang sudah di buat sebelumnya. Bila sudah relax sejenak seruput kopi yang ada. Next.
### A. Source Code
Berikut adalah Source Code dari program di atas
![img3](image/input.png)

### B. Penjelasan
```py
    from model.daftar_nilai import tambah_data, hapus_data, ubah_data
    from view.view_nilai import cari
```
- berfungsi untuk memanggil file lain di dalam satu module yang berbeda.
Sedangkan fungsi `def` dan module masih sama seperti pada penjelasan pertama.

# 3. VIEW NILAI
Untuk membuat module `view_nilai.py` pada package view yang sudah di buat sebelumnya.
### A. Source Code
Berikut adalah Source Code dari program di atas
![img4](image/view.png)

### B. Penjelasan
```py 
from model.daftar_nilai import data
```
- Berfungsi untuk memanggil data(dictionary) pada modul `daftar_nilai.py`.

```py
from tabulate import tabulate
``` 
- Berfungsi untuk mempermudah user dalam membuat table yang di inginkan. Sedangkan `tablefmt="double_grid"` berfungsi untuk membuat model atau jenis table sesuai yang diinginkan user.

# 4. MAIN

Terakhir saya membuat file `main.py` yang berisi code program untuk menyatukan semua fungsi yang ada di beberapa modul yang telah saya buat sebelumnya.

### A. Source Code
Berikut adalah Source Code dari program di atas
![img5](image/main1.png)
![img6](image/main2.png)

### B. Penjelasan
- `while True` Merupakan kondisi perulangan atau looping, di mana kode program akan dijalankan berulang kali sampai mendapatkan kondisi berhenti untuk mengulangnya.
- untuk memembuat perulangan pada pilihan menu yang akan tampil sebagai pilihan user. saya menggunakan fungsi
```py
if
elif
else
```
fungsi `if-else` untuk mengambil kondisi tertentu dan memeriksa apakah kondisinya benar atau salah. Jika kondisinya benar, maka pernyataan `if` mengeksekusi blok kode tertentu. Jika kondisinya salah, maka pernyataan else mengeksekusi blok kode yang berbeda.


# 5. HASIL OUTPUT

### Tambah Data
- Dokumentasi program tambah data
proses eksekusi
![img7](image/)
setelah eksekusi
![img8](image/11.png)

### Ubah Data
- Dokumentasi program ubah data
proses eksekusi
![img8](image/3.png)
setelah eksekusi
![img9](image/33.png)

### Cari Data
- Dokumentasi program cari data
![img10](image/4.png)

### Menampilkan Semua Data
- Dokumentasi program menampilkan data
![img11](image/5.png)

### Hapus Data
- Dokumentasi program Hapus data
![img12](image/2.png)

### Keluar Program
- Dokumentasi keluar program
![img13](image/6.png) 

# HAPPY NIC DAY :)





