# Script Auto Installer v2ray X-UI VPS UBUNTU
Dibawah ini adalah script auto installer v2ray x-ui di VPS Ubuntu yang bisa kalian gunakan secara gratis

...untuk tutorial cara installnya kalian bisa kunjungi artikel di blog saya yang [Update! Script Auto Installer V2ray Di VPS Ubuntu, Websocket + TLS + CDN](https://www.calonbos.net/script-auto-installer-v2ray-di-vps/) karena disini saya hanya membagikan scriptnya saja dan hanya untuk archive pribadi

### #1. Update System Linux Ubuntu

Untuk Perintahnya kalian bisa ketikan

``sudo apt update && apt upgrade -y``

### #2. Install Curl di Linux Ubuntu

Gunakan printah dibawah ini untuk melakukan instalasi curl, ini berfungsi untuk melakukan command pada protokol http atau https

``sudo apt install curl -y``

### #3. Install V2ray Dengan Panel X-UI

``Untuk script auto installer v2ray silahkan gunakan perintah dibawah ini``

### #4. Install Certificate

Untuk melakukan Install Certificate, gunakan perintah dibawah ini

``
apt install software-properties-common -y
apt install certbot -y
``

### #5. Buat Certificate

Silahkan ganti tulisan yang berwarna orange dengan email dan domain sebelum di eksekusi pada terminal, jika ada keterangan yang entah apa artinya, pokoknya ada dua pilihan yes/no, kalian pilih no saja dan enter.

``certbot certonly --standalone --preferred-challenges http --agree-tos --email email@calonbos.net -d sg-vpn.calonbos.net``

…jangan lupa untuk copas sertifikat yang didapatkan, ini berguna saat kita membuat akun v2ray kedepannya.

## Login WebUi V2ray (Panel X-UI)
Untuk melakukan login ke panel v2ray kalian cuku masukin ip vps di ikuti dengan port v2ray 54321, contohnya seperti ini

http://130.120.55.8:54321, selain itu kalian juga bisa login menggunakan subdomain yang sudah dibuat tadi di cloudflare dan diikuti dengan port v2ray. contoh, sg-vpn.calonbos.net:54321
 
Untuk user dan password panel v2ray menggunakan admin

semoga bisa bermanfaat buat teman-teman sekalian, saya doakan buat kalian yang sudah berkunjung dan subscribe ke channel youtube saya, semoga rezekinya selalu di lancarkan amin.
