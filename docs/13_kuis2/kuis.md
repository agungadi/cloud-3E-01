# 13 - Kuis 2 Build Image Docker dan Push Docker Hub

## Tujuan Pembelajaran

1. Agar dapat menjalankan build images repository kemudian melakukan push repository ke Docker Hub.


## Hasil Praktikum


1. Dikarenakan project UTS saya kemarin hilang maka saya membuat baru lagi pertama melakukan git clone project saya kedalam ubuntu.

![Screenshot Dashboard Oracle](img/1.png)


2. Kemudian Ls untuk cek project sudah ada di direktori ubuntu.

![Screenshot Dashboard Oracle](img/Screenshot_1.png)


3. Edit koneksi.php agar tersambung ke dalam mysql.

![Screenshot Dashboard Oracle](img/Screenshot_3.png)
![Screenshot Dashboard Oracle](img/Screenshot_2.png)


4. Project berhasil dijalankan di ip public ubuntu.

![Screenshot Dashboard Oracle](img/Screenshot_4.png)


5. Kemudian pada direktori project bookly buat file Dockerfile.

![Screenshot Dashboard Oracle](img/Screenshot_5.png)


6. Sudo nano dockerfile edit sesuai project yang di gunakan di sini menggunakan apache dan mysql.

![Screenshot Dashboard Oracle](img/Screenshot_6.png)


7. Kemudian lakukan build image project bookly tersebut.

![Screenshot Dashboard Oracle](img/Screenshot_7.png)
![Screenshot Dashboard Oracle](img/Screenshot_8.png)


8. Cek image pastikan build berhasil masuk images.

![Screenshot Dashboard Oracle](img/Screenshot_13.png)


9. Lalu lakukan docker login kemudian push project bookly ke docker hub seperto berikut ini :

![Screenshot Dashboard Oracle](img/Screenshot_9.png)


10. Kunjungi website docker hub kemudian cek bagian repository pastikan project kita sudah push ke docker hub seperti dibawah ini.

![Screenshot Dashboard Oracle](img/Screenshot_11.png)

