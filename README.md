## Install RocksDB

```bash
git clone https://github.com/facebook/rocksdb.git
cd rocksdb
sudo apt install libgflags-dev libsnappy-dev zlib1g-dev libbz2-dev liblz4-dev libzstd-dev
make shared_lib
sudo make install
```
