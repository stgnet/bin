bin
===

Bash Is Neat - convenient utility bash scripts making admin life easier

Project Description
-------------------

This is a set of random utilities that have been created to solve problems
administrating CentOS/RedHat/Fedora systems.  Predominately they are written
in bash, although that is not specifically a requirement for inclusion.

Requirements
------------

* a RedHat style system with yum (this could be made flexible later)
* bash
* root user access

Installation
------------

To install these utilities, log in (or su) as root, insure you are in /root,
and git clone this project like this:

 cd /root
 git clone http://github.com/stgnet/bin


Then just run the scripts present in the directory as
needed.  It may also be necessary to chmod +x /root/bin/*.  If you
get an error that the script is not found, you didn't su - and/or
/root/bin isn't in your $PATH - repeat the su - to fix.

Scripts
-------

* fix-resolv - add public dns servers  to /etc/resolv.conf to fix errors
		This can also be installed in crontab to patch after change
* fix-date - force an immediate ntpd resync to pool.ntp.org


LICENSE
-------

Public Domain

* Please share, fork, and contribute improvements
* If you don't like this, let me know why: scott@griepentrog.com
* If you like this, please buy me a beer: [GitTip](https://www.gittip.com/stgnet/)

