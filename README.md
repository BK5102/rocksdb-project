# rocksdb-project

## steps/commands used
  1. enable wsl
  2. install ubuntu
  3. sudo apt-get install g++
  4. install dependencies:
       sudo apt update  
       sudo apt-get install libsnappy-dev  
       sudo apt-get install zlib1g-dev  
       sudo apt-get install liblz4-dev 
       sudo apt-get install libzstd-dev  
5. build rocksdb
     git clone https://github.com/facebook/rocksdb.git
     cd rocksdb
     DEBUG_LEVEL=0 make shared_lib
     sudo make install-shared
     sudo ldconfig

## websites used 

https://github.com/facebook/rocksdb/blob/main/INSTALL.md#supported-platforms

https://docs.desmos.network/fullnode/rocksdb-installation/
