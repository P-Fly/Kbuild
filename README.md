Kbuild Manual
------------------------------

![](https://img.shields.io/aur/license/yaourt.svg)

## Usage

```
make clean
make defconfig
make
./vmlinux
```

Output:

```
Iterate over RBTree.
0x1 0x2 0x3 0x4 0x5 0x7 0x8 0x9 0x129 
Iterate over by postorder.
0x1 0x3 0x2 0x5 0x8 0x129 0x9 0x7 0x4
```