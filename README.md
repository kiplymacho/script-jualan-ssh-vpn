<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&lines=Channel+YouTube+@km7ujuh" />
</p>
<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&lines=K+I+P+L+Y+M+A+C+H+O" />
</p>
<h2 align="center">
Script Jualan SSH VPN

Powered By:

kiplymacho

<img src="https://img.shields.io/badge/Version-1.0.0-blue.svg"></h2>

</p> 

<h2 align="center"> Supported Linux Distribution</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"></p> 
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=purple"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=purple">  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=Lts&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=Lts&color=red">
</p>

<p align="center"><img src="https://img.shields.io/badge/Service-SSH_Over_Websocket-success.svg">  <img src="https://img.shields.io/badge/Service-OpenVPN_Over_Websocket-success.svg">  <img src="https://img.shields.io/badge/Service-SSH_Over_DNS-success.svg">  <img src="https://img.shields.io/badge/Service-SSLH-success.svg">  <img src="https://img.shields.io/badge/Service-Stunnel5-success.svg">  <img src= "https://img.shields.io/badge/Service-OHP_Open_Http_Puncher-success.svg">  <img src= "https://img.shields.io/badge/Service-SSTP_VPN-success.svg">  <img src= "https://img.shields.io/badge/Service-L2TP_VPN-success.svg">  <img src= "https://img.shields.io/badge/Service-PPTP_VPN-success.svg">
<p align="center"><img src="https://img.shields.io/badge/Service-SSH_OpenSSH-success.svg">  <img src="https://img.shields.io/badge/Service-SSH_Dropbear-success.svg">  <img src="https://img.shields.io/badge/Service-BadVPN-success.svg">  <img src="https://img.shields.io/badge/Service-OpenVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Squid3-success.svg">  <img   src="https://img.shields.io/badge/Service-Webmin-success.svg">  <img src="https://img.shields.io/badge/Service-SlowDns-success.svg">  <p align="center"><img src="https://img.shields.io/badge/Service-XRAY-success.svg">  <img src="https://img.shields.io/badge/Service-XRAY_Websocket_TLS-success.svg">  <img src="https://img.shields.io/badge/Service-XRAY_VLESS_VMESS-success.svg">  <img src="https://img.shields.io/badge/Service-XRAY_gRPC_VLESS_VMESS-success.svg">  <img src="https://img.shields.io/badge/Service-XRAY_TROJAN-success.svg">  <p align="center"><img src="https://img.shields.io/badge/Service-SSR-success.svg">  <img src="https://img.shields.io/badge/Service-Trojan_Go-success.svg">  <img src="https://img.shields.io/badge/Service-WireGuard-success.svg">  <img src= "https://img.shields.io/badge/Service-Shadowsocks-success.svg">

##### Script Membuat SSH Premium Untuk Di jual

##### Script Installer VPS by kiplymacho

Script auto installer VPS untuk memudahkan dalam berjualan SSH, VPN, dan Proxy

Sebelum menginstall script ini ada beberapa sistem yang dibutuhkan 

Pasang Aplikasi Termux Di Android Tetapi Untuk Aplikasi Termux Jangan Di Unduh Di Playstore Karena Bisa Menyebabkan Error,Unduh Aplikasi Termux Nya Di Link Ini:👉
[termux](https://sfile.mobi/1Pk3b69xugs7)

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

 - **Username untuk akun default** - masukkan username untuk akun SSH, VPN default. contoh: *kiplymacho*

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

</p>
<div height='45' align="center">
<h2>Contact me: <br>
</p>
  
<a href="https://github.com/kiplymacho"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" height='50'> </a>
<a href="https://facebook.com/kiplymachobanjar"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" height='50'> </a>
  
<a href="https://paypal.me/kiplymacho"> <img src="https://cdn.trakteer.id/images/embed/trbtn-red-6.png" height='50'> </a>
</h2>
</div>
<h2 align="center">
<img height=150 src="https://github-readme-stats.vercel.app/api/top-langs/?username=kiplymacho&layout=compact&theme=dark">
<img height=150 src="https://github-readme-stats.vercel.app/api?username=kiplymacho&count_private=true&show_icons=true&theme=dark">
<h2 align="center">

- Bila masih bingung bisa di tanyakan 
- [Facebook](https://www.facebook.com/httpcustomkiplymacho/)
- [WhatsApp](https://wa.me/6285751032225)

# _Follow_
- Klik Disini 👉[YouTube](https://www.youtube.com/@km7ujuh)
- Klik Disini👉[instagram](https://instagram.com/kiplymacho)
