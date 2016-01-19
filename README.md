to install

```bash
mkdir build
cd build
cmake ..
export C_INCLUDE_PATH=/usr/local/include
export CPLUS_INCLUDE_PATH=/usr/local/include
make
sudo make install
```

To build the tests, define the root of the gtest installation, e.g.

```
cmake .. -DGTEST_ROOT=/path/to/gtest
```

Test binaries have the suffix `_test`.
