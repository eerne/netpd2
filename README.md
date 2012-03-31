netpd2
======

### development setup

    netpd2/
    netpd2-patches/
 
- cd netpd2
- git checkout develop
- ln -s ../netpd2-patches/abs
- ln -s ../netpd2-patches/patches

- git remote add upstream git://github.com/reduzent/netpd2.git

### update

- git pull upstream master