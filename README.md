# CFT-Clash-for-Termux-Clash-Termux
CFT | Clash for Termux | Clash Termux

1.install termux FDROID

termux-setup-storage;pkg update -y;pkg upgrade -y;pkg install wget -y;wget https://github.com/MetaCubeX/mihomo/releases/download/v1.18.6/mihomo-android-armv7-v1.18.6.gz;gunzip mihomo-android-armv7-v1.18.6.gz;mv mihomo-android-armv7-v1.18.6 clash;cd /sdcard;mkdir /sdcard/clash;cd /sdcard/clash;wget https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geoip.dat;wget https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geosite.dat;wget https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/country.mmdb;wget https://github.com/haishanh/yacd/archive/gh-pages.zip;unzip gh-pages.zip;rm gh-pages.zip;wget https://raw.githubusercontent.com/DheMasker/Happy-Surfing/main/happysurfingcdn.yaml;chmod 755 ~/clash;cd $HOME;cd /sdcard && touch cft && nano cft

#!/data/data/com.termux/files/usr/bin/bash
./clash -d /sdcard/clash "$@"

mv cft /data/data/com.termux/files/usr/bin/;cd /data/data/com.termux/files/usr/bin/;chmod 755 cft;exit

2.APN home/internet proxy 127.0.0.1 port 7890 (TCP)
3.SOCKS5 UDP/socksdroid apk proxy 127.0.0.1 proxy 7891 (UDP BYPASS MODE com.termux) | https://github.com/bndeff/socksdroid/releases/

4.cft

5.yacd 127.0.0.1:9090/ui/#/




yacd 
https://github.com/haishanh/yacd/archive/gh-pages.zip

yacd meta
https://github.com/MetaCubeX/Yacd-meta/releases

yacd metacubex
https://github.com/MetaCubeX/metacubexd/releases
