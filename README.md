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
●	Pada ...


## 💻 CIDR (Classless Inter Domain Routing)
Perhitungan pada teknik CIDR (Classless Inter Domain Routing) berdasarkan jumlah komputer/ host yang ada di dalam subnet dengan menggunakan GN3.

● Melakukan labelling netmask dengan langkah-langkah sebagai berikut:




● Membuat topologi pada GNS3 sebagai berikut:
![ricky-topologi](https://user-images.githubusercontent.com/81076281/143621335-955199a5-10a8-4832-9edd-dc44ac798fad.PNG)
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
       address 192.186.18.1
       netmask 255.255.254.0
auto eth1
iface eth1 inet static
       address 192.186.16.2
       netmask 255.255.255.240
       gateway 192.186.16.1
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

● Pada router foosha lakukan perintah `iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE -s 192.186.0.0/16` agar terhubung ke internet

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
