Installation scripts
====================

This repository holds scripts that are used to install a Bunsen Labs environment on top of Debian. 
The script adds the jessie repos and Crunchbang waldorf repos, 
then installs a series of packages as outlined in John Raff's "Crunchbang Wally" install.
The script also installs the Bunsen Labs scripts and configs.

Installation
------------

Boot into your Debian Netinstall cli system,
log in and run these commands, as a normal user:
(A fresh copy of the bunsen-installscripts package will be downloaded.)

wget https://github.com/isaaclo123/bunsen-installscripts/archive/master.tar.gz

tar -xpf master.tar.gz

cd bunsen-installscripts-master

chmod +x INSTALL

sudo ./INSTALL


Bugs
----

For any bug or request [fill an issue][bug] on [GitHub][ghp].

  [bug]: https://github.com/BunsenLabs/scripts/issues
  [ghp]: https://github.com/BunsenLabs/scripts
