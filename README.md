Server Shield v1.1.5
=============

Server Shield is a lightweight method of protecting and hardening your Linux server. It is
easy to install, hard to mess up, and makes your server instantly and effortlessly resistant
to many basic and advanced attacks.

All IP addresses will be automatically detected and used for the firewall configuration.
Automatic security updates are enabled by default.

If you are running a modified version of Server Shield you should keep the self-updating of Server Shield off, so
your changes don't get overwritten.

*No maintenance required— just set it and forget it!*


Why Server Shield?
------------------

* You want protection that requires absolutely no configuration.
* You want protection that won't break stuff.
* You dislike complexity and favor simple solutions.
* You understand the importance of preventative measures
* You need exceptional performance.


Features
--------

* Slowloris Protection
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
------------
Server Shield depends on several pieces of open source software to function properly. If yum
is available, the following packages will be silently installed and kept up to date:

* yum-security
* iptables
* net-tools
* sed
* gawk
* git

Want to Help?
-----------
If you're interested in helping out, fork the project and start coding! The project is young
and there is still a lot of room for improvement. All comments, questions, conerns and suggestions are welcomed.