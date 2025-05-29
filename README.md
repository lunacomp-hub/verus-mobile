# verus-mobile
# Pertama Download semua Tools Nya disini
```
https://drive.google.com/drive/folders/17YVY54X0U30Pn1C5J8qqtL0aP0VX2yeT?hl=ID
```
# Download dan install config miningnya 
```
cd
curl -o /root/ccminer/run.sh https://raw.githubusercontent.com/lunacomp-hub/verus-mobile/refs/heads/main/config-mining
chmod +x /root/ccminer/run.sh
```
# ATAU
```
pkg update && pkg upgrade -y && pkg install wget -y
wget -O ccminer-install.sh https://raw.githubusercontent.com/lunacomp-hub/verus-mobile/refs/heads/main/ccminer-installer
chmod +x ccminer/ccminer-install.sh
./ccminer-install.sh
```
# Jalankan mining verus dengan perintah
```
cd ccminer && run.sh
```
Cara merubah Wallet Verus
```
nano /root/ccminer/run.sh
```
