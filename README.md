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
$ cmake . -DBUILD_TESTING=ONE -DCMAKE_PREFIX_PATH=/path/installed/to/
$ make -j4 tests
```
