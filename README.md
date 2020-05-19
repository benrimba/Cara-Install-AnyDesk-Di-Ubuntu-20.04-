# Cara Install AnyDesk Di Ubuntu 20.04
## Langkah 1: Perbarui Sistem Ubuntu
#```sudo apt update```
#```sudo apt -y upgrade [optional]```
## Langkah 2: Tambahkan repositori AnyDesk
```wget -qO - https://keys.anydesk.com/repos/DEB-GPG-KEY | sudo apt-key add -```
Kemudian tambahkan konten repositori AnyDesk ke sistem Ubuntu Anda.
```echo "deb http://deb.anydesk.com/ all main" | sudo tee /etc/apt/sources.list.d/anydesk-stable.list```
## Langkah 3: Instal AnyDesk di Ubuntu 20.04 / 18.04 LTS
```sudo apt update```
```sudo apt install anydesk```
## Langkah 4: Jalankan AnyDesk di Ubuntu 20.04 / 18.04
```anydesk```
## Finish
refer : [computingforgeeks.com](https://computingforgeeks.com/how-to-install-anydesk-on-ubuntu/)
