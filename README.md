Server Shield v1.0.6
=============

Server Shield is a lightweight method of protecting and hardening your Linux server. It is
easy to install, hard to mess up, and makes your server instantly and effortlessly resilient
to many basic and advanced attacks.

Automatic security updates are enabled by default, including the self-updating of Server Shield.
If you are running a modified version of Server Shield, you should turn self-updating off.
That way your changes don't get overwritten. Support for servers with multiple IP addresses
will be added soon.


Features
--------

* Firewall Hardening
* TCP Hardening
* Data Leakage Protection
* ICMP/Ping Flood Protection
* Rootkit Protection
* DoS Protection
* Spoof Protection
* SYN Flood Protection


Installation
------------

    git clone https://github.com/Brian-Holt/server-shield

    cd server-shield;chmod +x sshield;mv sshield /etc/init.d

    /etc/init.d/sshield start    


Requirements
--------
Server Shield depends on several pieces of open source software to function properly. These
packages will be automatically installed and kept up to date:

* yum
* yum-security
* iptables
* nmap
* net-tools
* sed
* gawk
* git