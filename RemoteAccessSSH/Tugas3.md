# Tugas Kelompok SSH-Server
**Nama Anggota Kelompok:**

1. Muhammad Gilang Ramadhan (2010131310005)
2. Reza Maulana ()

---

## Langkah - Langkah Penginstalan dan Konfigurasi SSH Server

- Langkah 1
![alt text](ssh-1.png)
Hal pertama yang harus kita lakukan adalah Masuk Debian Linux pada VirtualBox anda, masuk terminal, kemudian masuk sebagai user administrator. Jika sudah login, sekarang untuk penginstalan dengan mengetikkan "apt-get install openssh server" kemudian tekan ENTER.

<br>

- Langkah 2 <br>
![alt text](ssh-2.png)<br>
Jika proses penginstalan meminta file DVD, masuk ke mesin/machine yang terletak dibagian atas kiri virtual box.

<br>

- Langkah 3
![alt text](ssh-3.png)
Pilih Penyimpanan/Storage, lalu klik ikon DVD seperti dalam gambar.

<br>

- Langkah 4
![alt text](ssh-4.png)
Cari file DVD sesuai versi OS Linux yang dipakai, pilih file tersebut dan klik "OK"

<br>

- langkah 5
![alt text](ssh-6.png)
Disini tahap ini, penginstalan SSH sudah selesai. Selanjutnya kita akan mencoba masuk dari windows ke linux menggunakan aplikasi Putty. Bisa download menggunakan link dibawah  ini : https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html.<br>
Kemudian instal seperti biasa anda instal aplikasi lain.

<br>

- Langkah 6
![alt text](ssh-7.png)
Kembali ke Debian kita akan cek ip address kita dengan masukkan command "ip a". inet yang bertanda panah warna merah adalah ip address yang akan digunakan ke Putty 

<br>

- Langkah 7
![alt text](ssh-8.png)
Masukkan ip address sesuai inet, yaitu 192.168.10.1(sesuikan ip address milik anda) dengan port 22. Lalu klik open.

<br>

- Langkah 8
![alt text](ssh-9.png)
Hasil nya anda akan diminta login sesuai SuperUser di debian atau OS Linux yang lain yang anda pakai. Jika berhasil maka client sudah berhasil masuk dengan SSH