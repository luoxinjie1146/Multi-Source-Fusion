# NVDLA环境配置

* apt-get install g++ cmake libboost-dev python-dev libglib2.0-dev libpixman-1-dev liblua5.2-dev swig libcap-dev libattr1-dev
* wget -O systemc-2.3.0a.tar.gz http://www.accellera.org/images/downloads/standards/systemc/systemc-2.3.0a.tar.gz
* tar -xzvf systemc-2.3.0a.tar.gz
* cd systemc-2.3.0a
* mkdir -p /usr/local/systemc-2.3.0/
* mkdir objdir
* cd objdir
* ../configure --prefix=/usr/local/systemc-2.3.0
* make
* make install
* perl -MCPAN -e 'install "YAML"'
* apt install libio-tee-perl
* mv /bin/sh /bin/sh.bak
* ln -s /bin/bash /bin/sh