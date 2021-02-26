# mango

wget https://github.com/Haris131/mango/raw/main/badvpn_1.999.130-1_mipsel_24kc.ipk

wget https://github.com/Haris131/mango/raw/main/corkscrew_2.0-1_mipsel_24kc.ipk

Cara install badvpn 
==================
1. upload file ipk badvpn ke folder '/tmp' melalui winscp
2. install badvpn dengan comand berikut 

contoh install badvpn orangepizero :

opkg update && cd /tmp && opkg install --force-depends *.ipk

3. done , cek hasil nya di luci > system > software > installed package

note : jika dapat notif error depends udev abaikan aja 
