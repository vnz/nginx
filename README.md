Build nginx package
===================

* git-buildpackage -i -us -uc -b --git-ignore-branch --git-cleaner='git clean -dfx'


Upstream update
===============

* git-import-orig path/to/nginx\_1.6.1.orig.tar.gz
* dch -v "1:1.6.1-1" -M -D unstable "Upstream release nginx 1.6.1"
* commit now
* git tag 1.6.1-1


Extra modules
=============

* [echo](http://wiki.nginx.org/NginxHttpEchoModule)


