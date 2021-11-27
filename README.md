# Jarkom-Modul-4-C05-2021
Pengerjaan Soal Shift Modul 4 Jaringan Komputer 2021/2022 ( Modul Subnetting & Routing )         
.                                                           
Ghifari Astaudi U. (05111940000012)                             
Ricky Supriyanto (05111940000036)                                       
Cahyadesthian R. W. (05111940000156)                                   
.                                                               
# Praktikum Modul 3
### 📅 21 - 23 November 2021 
                  
### Topologi Soal : 

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/soal-shift.png" width="800"> 

## 💻 VLSM (Variable Length Subnet Masking)

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/pembagian.png" width="800"> 



#### Jumlah Alamat IP
Subnet, jumlah IP untuk mendapatkan netmask dari tiap subnet ditunjukkan oleh tabel berikut
| Subnet  | Jumlah IP | Netmask |
| :---         |     :---:      |          ---: |
| ------------- | ------------- | ------------- |
| A1  | 721 | /22 |
| A2  | 252 | /24 |
| A3  | 13 | /28 |
| A4  | 502 | /23 |
| A5  | 521 | /22 |
| A6  | 2 | /30 |
| A7  | 2 | /30 |
| A8  | 2 | /30 |
| A9  | 701 | /22 |
| A10  | 2 | /30 |
| A11 | 2021 | /21 |
| A12  | 101 | /25 |
| A13  | 1001 | /22 |
| Total  | 5841 | /19 |

### Tree

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/tree.png" width="800"> 

### Pengaturan Konfigurasi IP
●	Pada Foosha
1.	Mengarah Cloud                                                        
    192.168.72.13 subnet 255.255.255.252
2.	Mengarah Blueno                                             
    192.186.16.1 subnet 255.255.252.0
3.	Mengarah Server Doriki                                                              
    192.186.0.33 subnet 255.255.255.240
4.	Mengarah Guanhao                                                                          
    192.186.0.5 subnet 255.255.255.252
5.	Mengarah Water7                                                                                           
    192.186.0.9 subnet 255.255.255.252                                        

                                                          
                                                            
●	Pada Water7
1.	Mengarah Foosha                                                                     
    192.186.0.10 subnet 255.255.255.252
2.	Mengarah Cipher                                                                         
    192.186.12.1 subnet 255.255.255.0
3.	Mengarah Pucci                                                                                          
    192.186.0.13 subnet 255.255.255.252

●	Pada Pucci
1.	Mengarah Water7                                                                                     
    192.186.0.14 subnet 255.255.255.252
2.	Mengarah Jipangu                                                                                
    192.186.0.129 subnet 255.255.255.128
3.	Mengarah Courtyard dan Calmbelt                                                                             
    192.186.24.1 subnet 255.255.248.0

●	Pada Guanhao
1.	Mengarah Foosha                                                                     
    192.186.0.6 subnet 255.255.255.252
2.	Mengarah Jabra                                                                                      
    192.186.8.1 subnet 255.255.252.0
3.	Mengarah Alabasta                                                                     
    192.186.2.1 subnet 255.255.254.0
4.	Mengarah OIMO                                                                   
    192.186.0.1 subnet 255.255.255.252

●	Pada Alabasta 
1.	Mengarah Guanhao                                                                                                                                                          
    192.186.2.2 subnet 255.255.254.0 
2.	Mengarah Jorge                                                                                                   
    192.186.0.17 subnet 255.255.255.240

●	Pada OIMO
1.	Mengarah Guanhao                                                          
    192.186.0.2 subnet 255.255.255.252
2.	Mengarah Server Fukurou                                                     
    192.186.0.49 subnet 255.255.255.240
3.	Mengarah Seastone                                                                 
    192.186.1.1 subnet 255.255.255.0
                          
●	Pada Seastone
1.	Mengarah OIMO                                                                       
    192.186.1.2 subnet 255.255.255.0
2.	Mengarah Elena                                                                          
    192.186.4.1 subnet 255.255.252.0

●	Pada Jipangu

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/jipangu.png" width="800"> 


●	Pada Courtyard

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/courtyard.png" width="800"> 


●	Pada Calmbelt

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/calmbelt.png" width="800"> 


●	Pada Cipher

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/cipher.png" width="800"> 


●	Pada Blueno

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/blueno.png" width="800"> 


●	Pada Jabra

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/jabra.png" width="800"> 


●	Pada Maingate

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/maingate.png" width="800"> 


●	Pada Jorge

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/jorge.png" width="800"> 


●	Pada Enieslobby

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/enieslobby.png" width="800"> 

●	Pada Elena

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/elena.png" width="800"> 

●	Pada Fukurou

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/fukurou.png" width="800"> 

●	Pada Doriki

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/doriki.png" width="800"> 

Pada Server Doriki memiliki IP 192.186.0.32 
Pada Server Fukurou memiliki IP 192.186.0.48


### Pengaturan Routing
Untuk langkah nya bisa masuk kedalam router, lalu menekan menu static dan menambahkan data yang di inginkan


●	Pada Pada Foosha

1. 192.186.4.0/22 via 192.186.0.6
2. 192.186.1.0/24 via 192.186.0.6
3. 192.186.0.16/28 via 192.186.0.6
4. 192.186.2.0/23 via 192.186.0.6
5. 192.186.8.0/22 via 192.186.0.6
6. 192.186.0.0/30 via 192.186.0.6
7. 192.186.12.0/22 via 192.186.0.10
8. 192.186.0.12/30 via 192.186.0.10
9. 192.186.0.128/25 via 192.186.0.10
10. 192.186.0.48/28 via 192.186.0.6
11. 192.186.24.0/21 via 192.186.0.10


●	Pada Water7
1. 0.0.0.0/0 via 192.186.0.9
2. 192.186.24.0/21 via 192.186.0.14
3. 192.186.0.128/25 via 192.186.0.14


●	Pada Pucci
1. 0.0.0.0/0 via 192.186.0.13


●	Pada Guanhao
1. 0.0.0.0/0 via 192.186.0.5
2. 192.186.4.0/22 via 192.186.0.2
3. 192.186.1.0/24 via 192.186.0.2
4. 192.186.0.16/28 via 192.186.2.2
5. 192.186.0.48/28 via 192.186.0.2


●	Pada Alabasta
1. 0.0.0.0/0 via 192.186.2.1


●	Pada OIMO
1. 0.0.0.0/0 via 192.186.0.1
2. 192.186.4.0/22 via 192.186.1.2


●	Pada Seastone
1. 0.0.0.0/0 via 192.186.1.1


### Testing
Untuk testing sendiri dapat dilakukan dengan cara berikut:
1. Klik Menu `Add Simple PDU`
2. Pilih Source
3. Pilih Destination
4. Cek apakah ping tersebut success atau tidak


Berikut adalah contohnya:

<img src="https://github.com/Cahyadesthian-156/Jarkom-Modul-4-C05-2021/blob/main/img/simulasi.png" width="800">

## 💻 CIDR (Classless Inter Domain Routing)
Perhitungan pada teknik CIDR (Classless Inter Domain Routing) berdasarkan jumlah komputer/ host yang ada di dalam subnet dengan menggunakan GN3.

● Melakukan labelling netmask dengan langkah-langkah sebagai berikut:

**Langkah 1**
![ricky-langkah1](https://user-images.githubusercontent.com/81076281/143667092-af949808-4a4f-482f-bf45-a0ba029d84e6.png)

**Langkah 2**
![ricky-langkah2](https://user-images.githubusercontent.com/81076281/143667154-cacf0ca8-2e64-4b08-a066-bcce84b2efb2.png)

**Langkah 3**
![ricky-langkah3](https://user-images.githubusercontent.com/81076281/143667175-2dd2f297-5e26-4824-8ec0-e8468b536384.png)

**Langkah 4**
![ricky-langkah4](https://user-images.githubusercontent.com/81076281/143667203-bf0c4931-5de7-4b1a-8705-a8c152243207.png)

**Langkah 5**
![ricky-langkah5](https://user-images.githubusercontent.com/81076281/143667209-96ba060f-7bf9-4354-ade6-0ebd85e2ce94.png)

**Langkah 6**
![ricky-langkah6](https://user-images.githubusercontent.com/81076281/143667232-7406168e-16c6-4142-8c8f-62c6add91703.png)

● Lalu membuat tree sebagai berikut:
![ricky-tree](https://user-images.githubusercontent.com/81076281/143667203-bf0c4931-5de7-4b1a-8705-a8c152243207.png)

● Membuat topologi pada GNS3 sebagai berikut:
![ricky-topologi](https://user-images.githubusercontent.com/81076281/143666580-86015d35-4f27-47fa-8af8-896f80064d29.PNG)
● Membuat konfigurasi pada GNS3 sebagai berikut: 

**Foosha**
```
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
        address 192.186.64.1
        netmask 255.255.255.252

auto eth2
iface eth2 inet static
         address 192.186.192.1
         netmask 255.255.255.252

auto eth3
iface eth3 inet static
        address 192.168.1.1
        netmask 255.255.255.252

auto eth4
iface eth4 inet static
        address 192.186.32.1
        netmask 255.255.255.252
```
**Water7**
```
auto eth0
iface eth0 inet static
       address 192.186.192.2
       netmask 255.255.255.252
       gateway 192.186.192.1
auto eth1
iface eth1 inet static
       address 192.186.144.1
       netmask 255.255.255.252
auto eth2
iface eth2 inet static
         address 192.186.160.1
         netmask 255.255.252.0
```
**Pucci**
```
auto eth0
iface eth0 inet static
         address 192.186.144.2
         netmask 255.255.255.252
         gateway 192.186.144.1
auto eth1
iface eth1 inet static
         address 192.186.136.1
         netmask 255.255.255.128
auto eth2
iface eth2 inet static
         address 192.186.128.1
         netmask 255.255.248.0
```
**Guanhao**
```
auto eth0
iface eth0 inet static
          address 192.186.32.2
          netmask 255.255.255.252
          gateway 192.186.32.1
auto eth1
iface eth1 inet static
          address 192.186.20.1
          netmask 255.255.252.0
auto eth2
iface eth2 inet static
          address 192.186.8.1
          netmask 255.255.255.252
auto eth3
iface eth3 inet static
           address 192.186.16.1
          netmask 255.255.254.0
```
**Alabasta**
```
auto eth0
iface eth0 inet static
       address 192.186.16.2
       netmask 255.255.255.240
       gateway 192.186.16.1
auto eth1
iface eth1 inet static
       address 192.186.18.1
       netmask 255.255.254.0
```
**Oimo**
```
auto eth0
iface eth0 inet static
         address 192.186.8.2
         netmask 255.255.255.252
         gateway 192.186.8.1
auto eth1
iface eth1 inet static
          address 192.186.4.1
          netmask 255.255.255.0
auto eth2
iface eth2 inet static
           address 192.168.1.5
           netmask 255.255.255.252
```
**Seastone**
```
auto eth0
iface eth0 inet static
        address 192.186.4.2
        netmask 255.255.255.0
        gateway 192.186.4.1
auto eth1
iface eth1 inet static
        address 192.186.0.1
        netmask 255.255.252.0
```
**Blueno**
```
auto eth0
iface eth0 inet static
        address 192.186.64.2
        netmask 255.255.252.0
        gateway 192.186.64.1
```
**Chiper**
```
auto eth0
iface eth0 inet static
       address 192.186.160.2
       netmask 255.255.252.0
       gateway 192.186.160.1
```
**Jipangu**
```
auto eth0
iface eth0 inet static
	     address 192.186.136.2
	     netmask 255.255.255.128
	     gateway 192.186.136.1
```
**Calmbert**
```
auto eth0
iface eth0 inet static
	     address 192.186.128.2
	     netmask 255.255.248.0
	     gateway 192.186.128.1
```
**CourtYard**
```
auto eth0
iface eth0 inet static
       address 192.186.128.3
       netmask 255.255.248.0
       gateway 192.186.128.1
```
**Jabra**
```
auto eth0
iface eth0 inet static
        address 192.186.20.2
        netmask 255.255.252.0
        gateway 192.186.20.1
```
**EinesLobby**
```
auto eth0
iface eth0 inet static
         address 192.186.4.3
         netmask 255.255.255.0
         gateway 192.186.4.1
```
**Elena**
```
auto eth0
iface eth0 inet static
         address 192.186.0.2
         netmask 255.255.252.0
         gateway 192.186.0.1
```
**MainGate**
```
auto eth0
iface eth0 inet static
      address 192.186.16.3
      netmask 255.255.254.0
      gateway 192.186.16.1
```
**Jorge**
```
auto eth0
iface eth0 inet static
         address 192.186.18.2
         netmask 255.255.255.240
         gateway 192.186.18.1
```
**Fukurou**
```
auto eth0
iface eth0 inet static
	     address 192.168.1.6
	     netmask 255.255.255.252
	     gateway 192.168.1.5
```
**Doriki**
```
auto eth0
iface eth0 inet static
	    address 192.168.1.2
	    netmask 255.255.255.252
	    gateway 192.168.1.1
```
● Kemudian uncomment `net.ipv4.ip_forward=1` pada file `/etc/sysctl.conf` pada semua router.

● Pada router foosha lakukan perintah `iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE -s 192.186.0.0/16` untuk client agar terhubung ke internet dan `iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE -s 192.168.0.0/16` untuk server terhubung ke internet

● Lalu, lakukan routing dengan file `route.sh` pada dokumen `\root`. Kemudian jalankan dengan perintah  `source route.sh`

**Foosha**
```
route add -net 192.186.144.0 netmask 255.255.255.252 gw 192.186.192.2
route add -net 192.186.136.0 netmask 255.255.255.128 gw 192.186.192.2
route add -net 192.186.160.0 netmask 255.255.252.0 gw 192.186.192.2
route add -net 192.186.128.0 netmask 255.255.248.0 gw 192.186.192.2
route add -net 192.186.8.0 netmask 255.255.255.252 gw 192.186.32.2
route add -net 192.186.20.0 netmask 255.255.252.0 gw 192.186.32.2
route add -net 192.186.18.0 netmask 255.255.255.240 gw 192.186.32.2
route add -net 192.186.16.0 netmask 255.255.254.0 gw 192.186.32.2
route add -net 192.186.4.0 netmask 255.255.255.0 gw 192.186.32.2
route add -net 192.186.0.0 netmask 255.255.252.0 gw 192.186.32.2
#routing ke server-FUKUROU via OIMO
route add -net 192.186.1.4 netmask 255.255.255.252 gw 192.186.32.2
```
**Guanhao**
```
route add -net 192.186.4.0 netmask 255.255.255.0 gw 192.186.8.2
route add -net 192.186.0.0 netmask 255.255.252.0 gw 192.186.8.2
route add -net 192.186.18.0 netmask 255.255.254.0 gw 192.186.16.2
#routing ke server-FUKUROU via OIMO
route add -net 192.168.1.4 netmask 255.255.255.252 gw 192.186.8.2
```
**Water7**
```
route add -net 192.186.128.0 netmask 255.255.248.0 gw 192.186.144.2
route add -net 192.186.136.0 netmask 255.255.255.128 gw 192.186.144.2
```
**OIMO**
```
route add -net 192.186.0.0 netmask 255.255.252.0 gw 192.186.4.2
```
● Lalu mencoba beberapa testing dengan melakukan ping ke beberapa server atau client
**PING Fukurou -> Doriki**
![ricky-testing1](https://user-images.githubusercontent.com/81076281/143667423-ff6b4c40-53e2-48c1-89a5-cb73d5316654.jpg)

**PING Doriki -> Jorge**
![ricky-testing2](https://user-images.githubusercontent.com/81076281/143667503-231aad37-b334-4a81-8c2d-ae664a87a6bd.jpg)

**PING Fukurou -> Calmbert**
![ricky-testing3](https://user-images.githubusercontent.com/81076281/143667600-0ac8410a-3959-4322-a082-d01d80bb1741.PNG)

**PING Pucci-> Doriki**
![ricky-testing4](https://user-images.githubusercontent.com/81076281/143667652-33fb443a-684e-4c2f-a63a-2270caf3e583.PNG)

**PING Oimo -> Pucci**
![ricky-testing5](https://user-images.githubusercontent.com/81076281/143667740-1e0b0492-092c-4874-aa02-9a21cf549e6d.PNG)

**PING Pucci -> MainGate**
![ricky-testing6](https://user-images.githubusercontent.com/81076281/143667799-a6257f9e-51cb-4d10-8e02-63b2526b6188.PNG)

**PING EinesLobby-> MainGate**
![ricky-testing7](https://user-images.githubusercontent.com/81076281/143667841-a1482e6e-e5cc-4b71-bac5-f3fdfbb5baeb.PNG)

**PING Elena-> CourtYard**
![ricky-testing8](https://user-images.githubusercontent.com/81076281/143667917-a15cda5d-289d-45b2-84f0-9b27270b4890.PNG)

**PING Japra-> Jipangu**
![ricky-testing9](https://user-images.githubusercontent.com/81076281/143668080-d548c30d-d39d-4cb2-be5f-1e6e7913494a.PNG)

**PING google.com dari ELena**
![ricky-testing10](https://user-images.githubusercontent.com/81076281/143668096-27ccd097-5161-493f-a7ec-7c292dfbeaab.PNG)

**PING google.com dari Calmbert**
![ricky-testing10](https://user-images.githubusercontent.com/81076281/143668132-63d9f1eb-c3c9-4db3-a2cc-65a2296127eb.PNG)

**PING google.com dari Chiper**
![ricky-testing11](https://user-images.githubusercontent.com/81076281/143668204-b338adf4-0369-45da-a9fe-7cc9e7d238db.PNG)

**PING google.com dari Pucci**
![ricky-testing11](https://user-images.githubusercontent.com/81076281/143668500-d9f4a7a8-0147-4132-9d66-0a91c2bbd0b4.PNG)

**PING google.com dari EinesLobby**
![ricky-testing12](https://user-images.githubusercontent.com/81076281/143668596-a9e569da-5c7e-471d-8cdb-6b8f6afcbe7c.PNG)

**PING google.com dari Jorge**
![ricky-testing12](https://user-images.githubusercontent.com/81076281/143668635-b4cd3897-aac7-4bc8-a992-4746526b2d7d.PNG)

**Catatan**

Untuk ping ke google.com, setiap client atau server menggunakan perintah `echo nameserver 192.168.122.1 > /etc/resolv.conf`

### Kendala Praktikum:

-> Pada file .cpt tidak dapat melakukan pingdari server fukurou ke server doriki (sudah diselesaikan)

-> Tidak dapat menyambungkan 5 kabel dalam FOOSHA (sudah diselesaikan)

-> Saat dilakukan simulation ping pada file .cpt akan berjalan sangat lama

-> Pada mengerjakan GNS3, atur konfigurasinya ada yang kebalik atau salah pada netmask

-> Pada mengerjakan GNS3, kendala ngeping pada jorge dan pada server

-> Pada mengerjakan GNS3, kendala ngeping google pada client atau server
