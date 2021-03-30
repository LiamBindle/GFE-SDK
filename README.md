## Set up

```console
$ git clone https://github.com/LiamBindle/gf-sdk.git
$ git submodule update --init     # don't need --recursive
```

## Compiling
```console
$ mkdir build
$ cd build/
$ cmake ../gf-sdk -DCMAKE_INSTALL_PREFIX=/path/to/install/to
$ make -j4 install
```

## Running tests
```console
$ cmake . -DCMAKE_PREFIX_PATH=/path/installed/to/PFUNIT-4.2/cmake
$ make -j4 tests
```
