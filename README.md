mahimahi: a web performance measurement toolkit<br />
Solve Logging problem for high bandwidth scenarios <br />
<br />
Insturction:<br />
1-<br />
git clone https://github.com/Ppazhooh/mahimahi<br />
<br />
<br />
2-<br />
cd ~/mahimahi/<br /><br /> 
3- <br />
sudo apt-get install build-essential git debhelper autotools-dev dh-autoreconf iptables protobuf-compiler libprotobuf-dev pkg-config libssl-dev dnsmasq-base ssl-cert libxcb-present-dev libcairo2-dev libpango1.0-dev iproute2 apache2-dev apache2-bin iptables dnsmasq-base gnuplot iproute2 apache2-api-20120211 libwww-perl  <br /><br /> 4-<br />
./autogen.sh && ./configure <br /><br /> 5-<br />
remove effc++ from src/frontend/Makefile <br /><br /> 6-<br />



make  <br /><br /> 7-<br />
 sudo make install  <br /><br /> 8-<br />
 sudo sysctl -w net.ipv4.ip_forward=1<br />
