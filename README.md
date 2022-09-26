# **Membuat Microservice Sederhana**

## Download Project Marven
**Langkah 1  :** <br>Buat project Maven menggunakan Spring Initializr https://start.spring.io/
<br>**Langkah 2  :** <br>Pilih Maven Project pada pilihan project dan java pada pilihan bahasa
<br>**Langkah 3  :**<br> Pilih Spring Boot versi 2.6.11 M6 atau versi yang lebih tinggi. Jangan memilih versi snapshot.
<br>**Langkah 3  :** <br>Berikan nama grup pada project yang telah dibuat yaitu com.raihanefelmaulana
<br>**Langkah 4  :** <br>Berikan id Artefak pada projeck yaitu latihan-service yang otomatis akan mengisi bagian name
<br>**Langkah 5  :** <br>Tambahkan description untuk project yang akan kita buat
<br>**Langkah 6  :**<br>Pilih 17 pada bagian java, pastikan sesuai dengan jdk yang ada di pc/laptop.
<br>**Langkah 7  :** <br>Tambahkan dependensi yaitu Spring Web
![image.png](https://drive.google.com/uc?export=view&id=1VkIIwZShP97pUyYNCC7EMw0rvQeU8jVV )
<br>**Langkah 8  :** <br>Klik tombol Generate the project . File zip akan diunduh, ekstrak ke dalam hard disk.
<br>**Langkah 9  :**<br> Jalankan netbins lalu impor proyek pakar yang dibuat. Butuh beberapa waktu untuk mengunduh file yang diperlukan.
<br>**Langkah 10 :** <br>Lalu build and dependencies pada project yang sudah kita import
<br>**Langkah 11 :**<br> Sekarang jalankan LimitsServiceApplication, memulai Tomcat pada port (s) 8080 (http).

## Proyek Spring Boot
**Langkah 1 :** 
<br>  Menggunakan mulai.spring.io untuk membuat proyek "web". Dalam dialog "Dependenciesn" cari dan tambahkan Dependencies "web" seperti yang ditunjukkan pada tangkapan layar. Tekan tombol "Generate", unduh zip, dan buka kemasannya ke dalam folder di PC.
**Langkah 1 :**
<br>Buka proyek di IDE Anda dan cari DemoApplication.javafile di src/main/java/com/example/demofolder. Sekarang ubah isi file dengan menambahkan metode tambahan dan anotasi yang ditunjukkan pada kode di bawah ini. Anda dapat menyalin dan menempelkan kode atau cukup mengetiknya.

