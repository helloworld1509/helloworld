
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/helloworld1509/helloworld/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
