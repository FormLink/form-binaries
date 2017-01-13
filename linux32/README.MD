Compiled from [FORM master branch](https://github.com/vermaseren/form/commits/master), 13.01.2017, latest commit [fa1c759593506eb5eb09d12ebaf8a3e8bb81a0ad](https://github.com/vermaseren/form/commit/fa1c759593506eb5eb09d12ebaf8a3e8bb81a0ad) using (on Fedora 25, 64-bit)

```
sudo dnf install libstdc++-static.i686 glibc-static.i686 glibc-devel.i686 libstdc++-devel.i686 glibc-*.i686 gcc-c++.i686
./configure CFLAGS=-m32 CXXFLAGS=-m32 --disable-native --enable-static-link
make clean
make -j4
```
