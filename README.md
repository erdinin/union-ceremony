## union-ceremony
#### güncelleme ve masaüstü ortamının kurulması
```
sudo apt update && sudo apt upgrade -y
```
```
apt-cache search xfce4
```
#### xrdp
```
sudo apt install xrdp -y
```
```
sudo systemctl enable xrdp
sudo systemctl start xrdp
```
```
echo "xfce4-session" >~/.xsession
```
```
sudo ufw allow 3389/tcp
```
#### tarayıcı kurulması ve setup ceremony
```
sudo apt install firefox -y
```
```
apt install screen
```
```
screen -S union
```
```
sudo apt install curl iptables build-essential git wget jq make gcc nano automake autoconf tmux htop pkg-config libssl-dev tar clang unzip -y
```
```
sudo apt update
sudo apt install docker.io -y
```
```
docker --version
```
#### bu aşamadan sonra terminal açık kalsın ve biz kendi bilgisyarımızıa geçip diğer işlemlere devam edelim.
```
https://mobaxterm.mobatek.net/download-home-edition.html
adresine gidip pc ye indirelim ve çalıştıralım. oldukça basit bir kurulumu var.
```
