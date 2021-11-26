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
![topologi](https://user-images.githubusercontent.com/90148155/143158928-8362f14d-e3e1-4041-b7c9-e516978ae409.png)

## 💻 VLSM (Variable Length Subnet Masking)
![subnet](https://user-images.githubusercontent.com/90148155/143578001-e040b22b-de58-43cf-b1c0-bd28d0350c71.png)


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
![tree-vslm](https://user-images.githubusercontent.com/90148155/143574438-f063d69f-141b-44f5-88f5-b46dc8160cae.png)

### Pengaturan Konfigurasi IP
●	Pada Foosha
1.	Mengarah Cloud                                                        
    192.168.72.13 subnet 255.255.255.252
2.	Mengarah Blueno                                             
    192.186.16.1 subnet 255.255.252.0
3.	Mengarah Server Doriki                                                              
    192.168.73.30 subnet 255.255.255.252
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
    192.168.73.26 subnet 255.255.255.0
3.	Mengarah Seastone                                                                 
    192.186.1.1 subnet 255.255.255.0
                          
●	Pada Seastone
1.	Mengarah OIMO                                                                       
    192.186.1.2 subnet 255.255.255.0
2.	Mengarah Elena                                                                          
    192.186.4.1 subnet 255.255.252.0

●	Pada Jipangu
![ricky-onJipangu](https://user-images.githubusercontent.com/90148155/143575155-849bc36e-278a-40ca-8e68-6dcfb6256079.png)


●	Pada Courtyard
![ricky-onCourtyard](https://user-images.githubusercontent.com/90148155/143575653-2b39c906-3556-45ee-bbe9-d693eae1fb91.png)


●	Pada Calmbelt
![ricky-onCalmbelt](https://user-images.githubusercontent.com/90148155/143575674-a098a641-15ee-4ce5-9ac3-3d9dc0288874.png)


●	Pada Cipher
![ricky-onCipher](https://user-images.githubusercontent.com/90148155/143575688-6967dcd5-7408-4b99-8e6a-0c0eef058d39.png)


●	Pada Blueno
![ricky-onBlueno](https://user-images.githubusercontent.com/90148155/143575731-ab8ffb08-0110-4ff5-93e1-db2131ab0a9b.png)


●	Pada Jabra
![ricky-onJabra](https://user-images.githubusercontent.com/90148155/143575759-959dfb26-4378-4e61-a36f-15432f7fa38f.png)


●	Pada Maingate
![ricky-onMaingate](https://user-images.githubusercontent.com/90148155/143575781-932f8f6b-4ce0-44f1-8313-e049a9f6da3d.png)


●	Pada Jorge
![ricky-onJorge](https://user-images.githubusercontent.com/90148155/143575789-0ab0df7d-93ca-4aff-a34d-8b188e1ac159.png)


●	Pada Enieslobby
![ricky-onEniesLobby](https://user-images.githubusercontent.com/90148155/143575798-4f0c6895-9be7-4d12-af08-1ed3b0fbecfe.png)

●	Pada Elena
![ricky-onElena](https://user-images.githubusercontent.com/90148155/143575807-f4f9c62b-8f64-4ea9-b395-bc59ebb285fb.png)



### Pengaturan Routing
●	Pada ...


## 💻 CIDR (Classless Inter Domain Routing)
Perhitungan pada teknik CIDR (Classless Inter Domain Routing) berdasarkan jumlah komputer/ host yang ada di dalam subnet dengan menggunakan GN3.

● Melakukan labelling netmask dengan langkah-langkah sebagai berikut:




● Membuat topologi pada GNS3 sebagai berikut:
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
