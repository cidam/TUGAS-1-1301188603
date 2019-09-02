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

#### No.2 For If and Else ####

Program 1 :

[![Screen-Shot-2019-08-30-at-12-59-29.png](https://i.postimg.cc/1zhzQdnS/Screen-Shot-2019-08-30-at-12-59-29.png)](https://postimg.cc/qNwrcjxD)









