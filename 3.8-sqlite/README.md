Python 3.8 SQLite container image
=================================

This is a modification of [s2i-python-fedora](../3.8/README.md) container. Some packages were added to the `INSTALL_PKGS` variable in the Dockerfile.

Build normally, but use the tag `darkade/python-38-sqlite-fedora`

```
docker build . -t darkade/python-38-sqlite-fedora # build
docker push darkade/python-38-sqlite-fedora # deploy to docker hub
```
