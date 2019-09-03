## TUGAS 1 NETPRO ##


#### No.1 TCP Finite State Machine ####

Pada sisi Server :

* Mulai di starting point
* Lalu server akan melakukan listen terhadap client
* Server kemudian menerima SYN
* Server mengirim SYN, ACK
* Server menerima ACK
* Server melakukan proses connection estabilished
* Server menerima FIN dan mengirim ACK
* Server akan mengirim FIN lalu menutup koneksi

Pada sisi Client :

* Mulai di starting point
* Client membuka koneksi, mengirim SYN
* Client menerima respons SYN, menerima ACK
* Mengirim ACK, melakukan proses connection estabilished
* Client mengirim FIN, FIN 1 wait
* Client menerima ACK, FIN2 wait
* Client menerima FIN, mengirim ACK
* Client menunggu
* Time out, menutup koneksi

#### No.2 For and If Else ####

Program 1 :

[![Screen-Shot-2019-08-30-at-12-59-29.png](https://i.postimg.cc/1zhzQdnS/Screen-Shot-2019-08-30-at-12-59-29.png)](https://postimg.cc/qNwrcjxD)
<p align="center">
  <a> Gambar program 1 : For and If Else</a>
</p>

Pada program 1 ini, akan dilakukan sebuah perulangan for. Dimana outputnya nanti berupa hasil dari perulangan berdasarkan kondisi yang telah di tentukn. Contoh pada fungsi perulangan pertama, nilai i = 1. nilai i akan bertambah 1 di steiap perulangannya dan akan berhenti ketika nilai i = 3.

* For, melakukan sebuah perulangan berdasarkan kondisi yang telah ditentukan.
* Untuk menghentikan program dapat menggunakan fungsi break.
* Perulangan akan berhenti ketika bernilai false.

Program 2 :

[![Screen-Shot-2019-08-30-at-13-06-07.png](https://i.postimg.cc/9Mr6xdVk/Screen-Shot-2019-08-30-at-13-06-07.png)](https://postimg.cc/BLf7b1j5)
<p align="center">
  <a> Gambar program 2 : For and If Else</a>
</p>

Pada program 2 ini, sama halnya pada program 1. Di program ini juga akan menggunakan perulangan, tetapi perulangan yang digunakan berupa if else. If else ini merupakan sebuah perulangan yang dimana jika kondisi pertama tidak memenuhi, maka kondisi else yang akan di gunakan.

* If akan di jalankan ketika bernilai true, if else dijalankan ketika dalam kondisi yang berbeda dan else dijalankan ketika semuanya bernilai false.

#### No.3 Array and Function ####

Program 1 :

[![Screen-Shot-2019-08-30-at-13-28-53.png](https://i.postimg.cc/50mP24nw/Screen-Shot-2019-08-30-at-13-28-53.png)](https://postimg.cc/wy75WpKv)
<p align="center">
  <a> Gambar program 1 : Array and Function</a>
</p>

Pada program 1 ini, akan dibuat sebuah fungsi array untuk menampung sebuah nilai dari masing-masing index.

* Array meurpakan sekumpulan variable yang memilik tipe data yang sama dan dinyatakan dalam nama yang sama.
* Len dalam array digunakan untuk mengetahui panjang dari suatu array.

Program 2 :

[![Screen-Shot-2019-08-30-at-13-32-18.png](https://i.postimg.cc/KYMKBbpw/Screen-Shot-2019-08-30-at-13-32-18.png)](https://postimg.cc/VSzLPx8W)

<p align="center">
  <a> Gambar program 2 : Array and Function</a>
</p>

Pada program 2 ini, akan dibuat sebuah program yang akan menghasilkan output berupa penjumlahan. Dimana program ini memiliki tipe data interger dan merupakan function yang memiliki variable.

* Function merupakan sebuah blok kode yang melakukan tugas tertentu.
* Function baru akan berjalan ketika dipanggil.











