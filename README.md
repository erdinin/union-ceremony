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
#### bu aşamadan sonra terminal açık kalsın ve biz kendi bilgisyarımıza geçip diğer işlemlere devam edelim.
```
https://mobaxterm.mobatek.net/download-home-edition.html
adresine gidip pc ye indirelim ve çalıştıralım. oldukça basit bir kurulumu var.
kurulum tamamlandıktan sonra. sol üstten 'session' a tıklayıp açılan pencerede 'RDP' ye basacaksınız. 
remote host kısmı = ip adresiniz
username kısmı sunucu = root
port = 3389
şeklinde olacak ve ok a basıp bağlanın.
```

