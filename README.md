Server Shield v1.0.8
=============

Server Shield is a lightweight method of protecting and hardening your Linux server. It is
easy to install, hard to mess up, and makes your server instantly and effortlessly resistant
to many basic and advanced attacks.

Automatic security updates are enabled by default, including the self-updating of Server Shield.
If you are running a modified version of Server Shield, you should turn self-updating off so
your changes don't get overwritten.

Support for servers with multiple IP addresses will be added soon.

Features
--------

* Firewall Hardening
* TCP Hardening
* ICMP/Ping Flood Protection
* DoS Protection
* Spoof Protection
* FTP/SSH Bruteforce Protection
* Automatic Security Updates
* Disables Bash History
* DNS Amplification Protection


Installation
------------

    git clone https://github.com/Brian-Holt/server-shield

    cd server-shield;chmod +x sshield;mv sshield /etc/init.d

    /etc/init.d/sshield start    


Requirements
--------
Server Shield depends on several pieces of open source software to function properly. If yum
is available, the following packages will be silently installed and kept up to date:

* yum-security
* iptables
* nmap
* net-tools
* sed
* gawk
* git