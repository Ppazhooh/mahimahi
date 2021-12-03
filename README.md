mahimahi: a web performance measurement toolkit
Solve Logging problem for high bandwidth scenarios
Insturction:
git clone https://github.com/Ppazhooh/mahimahi
cd ~/mahimahi/
sudo apt-get install build-essential git debhelper autotools-dev dh-autoreconf iptables protobuf-compiler libprotobuf-dev pkg-config libssl-dev dnsmasq-base ssl-cert libxcb-present-dev libcairo2-dev libpango1.0-dev iproute2 apache2-dev apache2-bin iptables dnsmasq-base gnuplot iproute2 apache2-api-20120211 libwww-perl
./autogen.sh && ./configure && make
 sudo make install
 sudo sysctl -w net.ipv4.ip_forward=1
