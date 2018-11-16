To build TURN server:

$ wget https://github.com/downloads/libevent/libevent/libevent-2.0.21-stable.tar.gz
$ sudo -s
# tar xvfz libevent-2.0.21-stable.tar.gz
# cd libevent-2.0.21-stable
# ./configure
# make
# make install

$ ./configure
$ make
$ sudo -s
# make install

Setup and Deploy:

# cp /usr/local/etc/turnserver.conf.default /etc/turnserver.conf
# nohup /usr/local/bin/turnserver &
