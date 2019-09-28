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

#### No.4 Struct and Method ####

[![Screen-Shot-2019-08-30-at-13-54-26.png](https://i.postimg.cc/pLXhFYWH/Screen-Shot-2019-08-30-at-13-54-26.png)](https://postimg.cc/kBzgrSR1)

<p align="center">
  <a> Gambar program 1 : Struct and Method</a>
</p>

Pada program 1 ini, akan dibuat sebuah program menggunakan funsi struct. Fungsi struct merupakan suatu struktur data yang menggabungkan beberapa data dengan berbagai tipe data yang memiliki ukuran yang berbeda (terdiri dari 1 atau lebih variable yang bertipe data sama/berbeda) di kelompokan dalam satu deklarasi unik dan saling berkaitan. Program ini akan menghasilkan output berupa nama dan umur.

* Tipe data pada di assign name dan age untuk memberikan nilai ke parameter. Nilai atribut tersebut dipanggil satu persatu dengan urutan tipe data.

[![Screen-Shot-2019-08-30-at-14-00-17.png](https://i.postimg.cc/sXyv3p0q/Screen-Shot-2019-08-30-at-14-00-17.png)](https://postimg.cc/948Wpq2Y)

<p align="center">
  <a> Gambar program 2 : Struct and Method</a>
</p>

Pada program 2 ini, sama pada program pertama yaitu sama-sama menggunakan fungsi struct. Tetapi yang membedakan program 1 dan 2 ialah struct pada program ke-2 sudah di inisialisasi terlebih dahulu.

#### No.5 Multiple Return Value and Command Line ####

[![Screen-Shot-2019-08-30-at-14-03-55.png](https://i.postimg.cc/xTrTQGJR/Screen-Shot-2019-08-30-at-14-03-55.png)](https://postimg.cc/nMktYD1j)

<p align="center">
  <a> Gambar program 1 : Multiple Return Value and Comman Line</a>
</p>

Pada program 1 ini, akan dibuat sebuah program yang akan menghasilkan output berupa nilai 3,7,7. Nilai lebih dari 1 akan dikembalikan oleh sebuah fungsi menggunakan tuple.

[![Screen-Shot-2019-08-30-at-14-12-34.png](https://i.postimg.cc/rp2StRPC/Screen-Shot-2019-08-30-at-14-12-34.png)](https://postimg.cc/cvTKpCZr)

<p align="center">
  <a> Gambar program 2 : Multiple Return Value and Comman Line</a>
</p>

Pada program 2 ini,  akan dihasilkan sebuah  output word: foo, numb:42, fork:false, svar:bar, tail:[]. program ini menggunakan command line (flag) , fungsinya untuk mencetak nilai flag. Flag di deklarasikan dengan cara di assign ke dalam pointer.

#### No.6 Simple Web Apps ####

[![Screen-Shot-2019-08-30-at-14-23-37.png](https://i.postimg.cc/C1sTV8Wv/Screen-Shot-2019-08-30-at-14-23-37.png)](https://postimg.cc/5YykBX9v)

<p align="center">
  <a> Gambar program  : Simple Web Apps</a>
</p>

Pada program ini, akan dibuat sebuah program server client. Dimana server menunggu client untuk mengkases program melalui localhost dengan port 8000 dan menampilkan pesan yang di kirimkan.

#### No.7 Config File ####

[![Screen-Shot-2019-09-28-at-18-07-57.png](https://i.postimg.cc/DZs3MdpY/Screen-Shot-2019-09-28-at-18-07-57.png)](https://postimg.cc/R6MY3fBc)

<p align="center">
  <a> Gambar program  : Config File</a>
</p>

Pertama kita akan membuat file berupa config.json untuk melakukan konfigurasi. Pada file config.json ini terdapat tipe data server dan memiliki atribut berupa port. Fungsi http pada Go digunakan untuk mengambil nomor port dari file config.json dengan menggunakan viper (sintaks viper.GetString(“server.port”)), yang nantinya akan mengembalikan nilai port dari tipe data server didalam file konfig.json.












