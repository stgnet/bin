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

* a RedHat style system with yum (some scripts now work on Ubuntu/Debian) 
* bash (well, yeah)
* sed (used for mangling config files)
* root user access via sudo
* In most cases dependencies are checked and the script attempts to install
  what it needs.  If this doesn't work for you, please let me know.

Installation
------------

To install these utilities, log in to your user account, insure you are
in the ~ (home) directory, and git clone this project like this:

	cd ~
	git clone http://github.com/stgnet/bin

Then just run the scripts as needed.  If you get an error that the script
is not found, you don't have $HOME/bin appended to your path or you need
to log in again for bash to realize it's now there.

Scripts
-------

* install-whatever - install a component that needs more than just yum
* build-asterisk - tool for building Asterisk from source with dev options
* fix-date - force an immediate ntpd resync to pool.ntp.org
* sshkey - install key on remote system for no-prompt ssh/scp/rsync access
* webconf - auto build apache virtual.conf from /var/www/domain.com directories

LICENSE
-------

Public Domain - why? Becuase you should be free to do whatever you want with these.

* Please share, fork, and contribute improvements
* If you don't like this, let me know why: scott@stg.net or @stgnet
* If you like this, please buy me a beer: [GitTip](https://gratipay.com/~stgnet/) or paypal@stg.net

