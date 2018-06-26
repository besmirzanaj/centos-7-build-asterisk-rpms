# centos-7-build-asterisk-rpms
How to build asterisk rpms on Centos 7

Download Asterisk from here
http://downloads.asterisk.org/pub/telephony/asterisk/releases/

This spec file covers the installation of version asterisk-14.6.1.tar.gz

Dependencies:
yum groupinstall "Development Tools"

yum install \
	bison doxygen flex gmime-devel iksemel-devel  jansson-devel  
	libcap-devel  libedit-devel gsm-devel libical-devel \
	libtiff-devel  libuuid-devel ncurses-devel  neon-devel \
	net-snmp-devel  newt-devel openssl-devel pam-devel popt-devel \
	spandsp-devel  speex-devel sqlite-devel libsrtp-devel \
	uriparser-devel gcc-c++ 
 