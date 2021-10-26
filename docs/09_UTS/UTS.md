# 08 - UTS

## Tujuan Pembelajaran

1. dapat menyimpan atau mengambil data langsung dari internet 
atau dari dalam platform cloud
2. Dapat menampilkan file dari Object Storage ke Wordpress
3. Konfigurasi VM 
4. DB Instace Import sql ke database Wordpress

## Hasil Praktikum Wordpress + Object Storage

1. Upload Terlebih dahulu file image ke object storage.

![Screenshot Dashboard Oracle](img/Screenshot_3.png)


2. Setelah berhasil di upload klik object details salin link URI image.

![Screenshot Dashboard Oracle](img/Screenshot_4.png)

3.  Paste URI ke dalam komponen image di wordpress

![Screenshot Dashboard Oracle](img/Screenshot_6.png)



4. Upload lagi file image untuk sampul buku.

![Screenshot Dashboard Oracle](img/Screenshot_7.png)

5. Salin uri nya kemudian paste pada komponen image di wordpress.

![Screenshot Dashboard Oracle](img/Screenshot_8.png)

6. Kemudian akan tampil sampul foto yang di ambil dari object storage.

![Screenshot Dashboard Oracle](img/Screenshot_9.png)
![Screenshot Dashboard Oracle](img/Screenshot_16.png)

7. Berikutnya akan mencoba upload file video pada object storage.

![Screenshot Dashboard Oracle](img/Screenshot_36.png)

8. Pada komponen video di wordpress paste url dari object storage.

![Screenshot Dashboard Oracle](img/Screenshot_37.png)

9. Maka video berhasil di insert pada wordpress.

![Screenshot Dashboard Oracle](img/Screenshot_38.png)

10. Selanjutnya melakukan upload file pdf pada object storage.

![Screenshot Dashboard Oracle](img/Screenshot_31.png)


10. Setelah berhasil di upload salin URI file pdf tersebut.

![Screenshot Dashboard Oracle](img/Screenshot_32.png)


10. Paste uri ke link text yang nanti sebagai object click.

![Screenshot Dashboard Oracle](img/Screenshot_33.png)


11. Lalu coba kunjugi wordpress kemudian klik object read yang tadi ada link uri pdf, akan direct download pdf yang berada di object storage.

![Screenshot Dashboard Oracle](img/Screenshot_39.png)

##  Hasil Praktikum Wordpress + VM + DB Instance

1. Pertama lakukan import file sql book yang berisi data table buku ke database wordpress.

![Screenshot Dashboard Oracle](img/Screenshot_22.png)


2. Lalu Cek pada database wordpress apa sudah berhasil di import untuk table buku.

![Screenshot Dashboard Oracle](img/Screenshot_24.png)


3. Kemudian menuju folder /var/www/html/wp-content/themes edit script php untuk membaca database table buku seperti di bawah ini.

![Screenshot Dashboard Oracle](img/Screenshot_26.png)


4. Setelah itu akses wordpress untuk melihat table yang read dari database wordpress buku

![Screenshot Dashboard Oracle](img/Screenshot_27.png)




## Tampilan website Wordpress

### Link Wordpress : http://140.83.52.211/index.php/blog/

1. Home

![Screenshot Dashboard Oracle](img/Screenshot_40.png)

2. Tables Header List Buku

![Screenshot Dashboard Oracle](img/Screenshot_41.png)

3. Rules 

![Screenshot Dashboard Oracle](img/Screenshot_42.png)

4. Buku

![Screenshot Dashboard Oracle](img/Screenshot_43.png)
![Screenshot Dashboard Oracle](img/Screenshot_44.png)
![Screenshot Dashboard Oracle](img/Screenshot_45.png)

5. Contact

![Screenshot Dashboard Oracle](img/Screenshot_46.png)




