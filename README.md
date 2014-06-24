Build nginx package
=====================

* debian/rules clean
* git-buildpackage -i -us -uc -b


Upstream update
===============

* git-import-orig path/to/nginx\_1.6.1.orig.tar.gz
* dch -v "1:1.6.1-1" -M -D unstable "Upstream release nginx 1.6.1"
* commit now
* git tag 1.6.1-1


