# mango

Cara install badvpn 
==================
1. upload file ipk badvpn ke folder '/tmp' melalui winscp
2. install badvpn dengan comand berikut 

contoh install badvpn orangepizero :

opkg update && cd /tmp && opkg install --force-depends *.ipk

3. done , cek hasil nya di luci > system > software > installed package

note : jika dapat notif error depends udev abaikan aja 
