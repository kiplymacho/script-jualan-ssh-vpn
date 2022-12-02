##### Script Membuat SSH Premium Untuk Di jual

##### Script Installer VPS by kiplymacho

Script auto installer VPS untuk memudahkan dalam berjualan SSH, VPN, dan Proxy

Sebelum menginstall script ini ada beberapa sistem yang dibutuhkan 

Pasang Aplikasi Termux Di Android Tetapi Untuk Aplikasi Termux Jangan Di Unduh Di Playstore Karena Bisa Menyebabkan Error,Unduh Aplikasi Termux Nya Di Link Ini:

https://sfile.mobi/1Pk3b69xugs7

Kemudian Kalian Harus Mempunyai ip vps Dan ip Vps Nya Sudah Di Jadikan Domain . Kalau Sudah Membuat ip vps Dan Dijadikan Domain Masuk Ke Aplikasi Termux Dan Login Kan ip vps nya di termux !! Kemudian 

##### Installation

Untuk instalasi script silahkan jalankan perintah berikut:

$ wget https://raw.githubusercontent.com/kiplymacho/script-jualan-ssh-vpn/master/centos-kvm.sh

$ chmod +x centos-kvm.sh

$ sh centos-kvm.sh

atau bisa aja langsung yg dibawah ini

$ wget https://raw.githubusercontent.com/kiplymacho/script-jualan-ssh-vpn/master/centos-kvm.sh && chmod +x centos-kvm.sh && sh centos-kvm.sh

Perintah diatas akan menginstall script auto installer. Anda akan disuruh untuk mengisi:


 - **Nama Pemilik Server** - silahkan masukkan nama pemilik server.

 - **Nomor HP atau Email Pemilik Server** - silahkan masukkan nomor / email.

 - **Username untuk akun default** - masukkan username untuk akun SSH, VPN default. contoh: *khairil*

 - **Maks Login User** - masukkan limit login user. contoh: 1 (untuk melimit user hanya bisa 1 kali login)


##### Feature


##### Layanan yang diaktifkan pada script ini:


 - **OpenVPN** : TCP 1194 (client config : http://IP:81/client.ovpn )

 - **Port OpenSSH** : 22, 143

 - **Port Dropbear** : 80, 109, 110, 443

 - **SquidProxy** : 8080, 3128 (limit to IP SSH)

 - **Nginx** : 81

 - **badvpn** : badvpn-udpgw port 7300

 - **Webmin** : http://IP:10000/

 - **vnstat** : http://IP:81/vnstat/

 - **MRTG** : http://IP:81/mrtg/

 - **Timezone** : Asia/Jakarta

 - **Fail2Ban** : [on]

 - **Root Login on Port 22** : [disabled]

 - **IPv6** : [off]


##### Beberapa fitur yang tersedia saat ini:


 - **speedtest --share** : untuk cek speed vps,

 - **mem** : untuk melihat pemakaian ram,

 - **checkvirus** : untuk scan virus / malware,

 - **bench** : untuk melihat performa vps,

 - **usernew** : untuk membuat akun baru,

 - **userlist** : untuk melihat daftar akun beserta masa aktifnya,

 - **userlimit *(limit)*** : untuk kill akun yang login lebih dari *(limit)*. Cth: userlimit 1,

 - **userlogin** : untuk melihat user yang sedang login,

 - **userdelete** : untuk menghapus user,

 - **trial** : untuk membuat akun trial selama 1 hari,

 - **renew** : untuk memperpanjang masa aktif akun,

 - **info** : untuk melihat ulang informasi ini.


##### Beberapa alat atau tools yang dapat Anda gunakan:

<pre>axel, bmon, htop, iftop, mtr, nethogs</pre>

##### Jangan Lupa Klik Kotak Dibawah ini 

<p align="center">
  Follow Me On
</p>
<p align="center">
  <a href="https://www.youtube.com/@km7ujuh?sub_confirmation=1">
    <img src="https://github.com/th3unkn0n/extra/blob/master/.img/yt.png" width="40" height="40">
  </a>
  <a href="https://www.instagram.com/kiplymacho/">
    <img src="https://github.com/th3unkn0n/extra/blob/master/.img/ig.png" width="40" height="40">
</p>
