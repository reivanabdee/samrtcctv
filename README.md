# project semester 6 (on Progress)
Berbasis dual Camera, 
1 Untuk mengidentifikasi pemilik toko di sekitar area toko
Dan 1 lagi untuk memantau area (garasi/toko)

# Cara kerja
Jika kamera utama (1) tidak mendeteksi pemilik toko, maka kamera kedua akan otomatis menyala. Sebaliknya, jika kamera utama mendeteksi pemilik toko maka kamera pemantau (2) akan mati. Nantinya sistem ini akan memakai YOLO dan dapat mengklasifikasi jenis bahaya atau ancaman pencurian dengan alarm *jika sudah melewati garis merah (level 3) 







![gif](https://github.com/reivanabdee/samrtcctv/blob/main/cctv.gif)

# Settingan kamera ke 2
Untuk kamera kedua menggunakan aplikasi android <a href="https://s3.apk4all.com/apps/2020/11/1/IP_Webcam_Pro_v1.15.0r.768_Apk4all.com.apk">IP Webcam Pro</a> , dengan menggunakan satu jaringan yang sama. Adapun settingannya sebagai berikut: 

![png](https://github.com/reivanabdee/samrtcctv/blob/main/Screenshot_2022-04-21-04-42-45_1366x768.png)
![png](https://github.com/reivanabdee/samrtcctv/blob/main/Screenshot_2022-04-21-04-42-27_1366x768.png)

# catatan 
 cctv2.ipynb adalah alternatif jika cctv.ipynb tidak bisa running
