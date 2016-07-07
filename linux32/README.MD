Compiled from [FORM master branch](https://github.com/vermaseren/form/commits/master), 4.07.2016, latest commit [805031bb6ae398ee6a60e0f8be5b2dc7cce872a6](https://github.com/vermaseren/form/commit/805031bb6ae398ee6a60e0f8be5b2dc7cce872a6) using (on Fedora 23, 64-bit)

```
sudo dnf install libstdc++-static.i686 glibc-static.i686 glibc-devel.i686 libstdc++-devel.i686 glibc-*.i686 gcc-c++.i686
./configure CFLAGS=-m32 CXXFLAGS=-m32 --disable-native --enable-static-link
make clean
make -j4
```
