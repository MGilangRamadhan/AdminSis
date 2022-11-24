# Tugas Kelompok DNS
**Nama Anggota Kelompok:**

1. Muhammad Gilang Ramadhan (2010131310005)
2. Reza Maulana (2010131310012)

---

## Langkah - Langkah Penginstalan dan Konfigurasi DNS 

- Langkah 1
![alt text](dns1.png)
masuk terminal pada os linux anda, login sebagai SuperUser. Masukkan perintah apt-get install bind9, tunggu penginstalan sampai selesai

<br>

- langkah 2
![alt text](dns2.png)
![alt text](dns3.png)
kemudian masukkan perintah "nano db.reza(menyesuikan nama db kalian)" kemudian ikuti seperti gambar diatas.<br>
Note : ip sesuaikan ip address server, localhost bisa kalian ubah sesuai kehendak kalian. Jika sudah, simpan dengan menekan ctrl+x kemudian enter

<br>

- langkah 3
![alt text](dns4.png)
Kemudian masukan "nano db.192" ikuti seperti digambar

<br>

- langkah 4
![alt text](dns5.png)
selanjutnya, "nano named.conf.options" kemudian sesuikan ip dengan ip address server kalian

<br>

- langkah 5
![alt text](dns7.png)
"nano named.conf.local"

<br>

- langkah 6
![alt text](dns8.png)
"nano /etc/resolv.conf" sesuikan search dan name server anda.

<br>

- langkah 7
![alt text](dns9.png)
Selanjutnya install dengan perintah "apt-get install dnsutils" setelah selesai lakukan uji coba dengan perintah "nslookup reza.com(menyesuaikan nama web kalian)" maka akan tampil seperti gambar diatas

- langkah 8
![alt text](dns10.png)
pengujian selanjutnya bisa dengan masukan perintah "dig reza.com" yang akan tampil seperti gambar.