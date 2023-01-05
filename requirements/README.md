## Requirements

OpenVDB dependencies:

```bash
apt-get install -y libboost-iostreams-dev
apt-get install -y libtbb-dev
apt-get install -y libblosc-dev
```

Build OpenVDB 9.1.0.

```bash
cd openvdb-9.1.0
mkdir build
cd build
cmake ..
make -j4 && make install
```


