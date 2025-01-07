# technitium-wg
Technitium + Wireguard Debian 12
## instalacion wireguard y Technitium Debian 12
Wireguard nos permite tener acceso remoto a un equipo o ip por ejemplo a las DNS
Technitium es un servidor DNS que ademas incluye el bloqueo de publicidad por medio listas y del dns.

##Instalacion Wireguard
```
apt update && apt install sudo dnsutils curl -y
wget -O wireguard.sh https://get.vpnsetup.net/wg
sudo bash wireguard.sh
```

##Instalacion de technitium
```
curl -sSL https://download.technitium.com/dns/install.sh | sudo bash
```
```
ping google.com
```
###Acceso desde
```
http://IP:5380/
```
```
#Settings/General
#DNS Server Local End Points
127.0.0.1:53
10.7.0.1:53
```



###settings/blocking
```
https://big.oisd.nl/
https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
```
