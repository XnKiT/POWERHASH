# POWERHASH

Design, development and Optimize Crypto algorithms.

Algorithms
-------

- **Blake256** (crypto/blake256.c)
- **Groestl** (crypto/groestl.c)
- **Jh** (crypto/jh.c)
- **Keccak** (crypto/keccak.c) (Optimization is not done)
- **Skein** (crypto/skein.c)

Compile and Building
-------------------

```
$ git clone https://github.com/xNKIT/POWERHASH
$ cd POWERHASH
$ mkdir _build
$ cd _build
$ cmake ..
$ sudo make -j8
$ sudo make install
$ ./POWERHASH
```
