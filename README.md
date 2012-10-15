Server Shield v1.0.5
=============

Server Shield is a lightweight method of protecting and hardening your Linux server. It is
easy to install, hard to mess up, and makes your server instantly and effortlessly resilient
to many basic and advanced attacks.

All requirements automatically install and are kept up to date. You may change
the update setting to also enable Server Shield's self-updating, or to disable all updates.

IP address and ethernet interface are automatically detected. Support for servers with
multiple IP addresses will be added soon.


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


Requirements
--------

* iptables
* nmap
* net-tools
* yum


Installation
------------

    git clone https://github.com/Brian-Holt/server-shield

    cd server-shield;chmod +x sshield;mv sshield /etc/init.d

    /etc/init.d/sshield start    
