# setting mikrotik
1. Menghubungkan Router Langkah yang harus dilakukan adalah menghubungkan port Enther 1 router ke kabel WAN dan menghubungkan PC ke Ether2. Setelah itu, buka WinBox dan cari ruter yang sedang digunakan kemudian klik tombol 'Connect' untuk menghubungkan ke router tersebut.
  
2. Setting Konfigurasi IP Address Berikut langkah-langkahnya.
  
 Buka jendela 'Bridge' kemudian klik tab 'Bridge'. Tekan tombol (+) dd untuk membuka dialog baru. Masukkan nama jembatan lokal lalu klik OK.

 Klik tab 'Ports' lalu klik tombol (+). Nantinya ada jendela baru yang terbuka dan pilih Interface Ether2. Setelah itu pilih Local di bagian Bridge dan tekan OK.

 Buka IP dan klik Addresses lalu masukkan tombol (+). Masukkan 192.168.88.1/24 dan pilih 'Local' di bagikan 'Interface'. Tekan 'OK'. 

3. Setting Konfigurasi DHCP Server Setelah konfigurasi IP Address selesai, proses selanjutnya adalah mengatur konfigurasi DHCP Server DHCP.

  Caranya buka IP kemudian klik 'DHCP Server'. Setelah itu tekan tombol DHCP Set up untuk membuka jendela baru. Klik 'Lokal' pada 'Antarmuka Server DHCP' dan klik 'Berikutnya'.

4. Setting Konfigurasi Jaringan Internet Cara konfigurasinya bisa dengan membuka kategori segmen PPP dan klik tab Interfaces.
Selanjutnya klik tombol (+) dan pilih 'PPPoE Client'. Klik 'Ether 1' dibagian 'Interfce' dan klik 'OK'.

Setelah semua konfigurasi berhasil, pengguna dapat mengakses Internet dari router. Lakukan verifikasi konektivitas diketahui IP dengan melakukan Ping ke Alamat IP yang server Google 5. Buat Kata Sandi Apabila berhasil terhubung, buat kata sandi untuk meningkatkan keamanan minimal 12 karakter dengan angka, simbol, kapital, dan huruf kecil.
