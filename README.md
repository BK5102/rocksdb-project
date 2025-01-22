# rocksdb-project

## steps/commands used
  1. created a project folder named rocksdb and inside that I cloned the repository and built it locally.
  2. enable wsl
  3. install ubuntu
  4. sudo apt-get install g++
  5. install dependencies:
       sudo apt update  
       sudo apt-get install libsnappy-dev  
       sudo apt-get install zlib1g-dev  
       sudo apt-get install liblz4-dev 
       sudo apt-get install libzstd-dev  
6. build rocksdb  
     git clone https://github.com/facebook/rocksdb.git  
     cd rocksdb  
     make static_lib

## websites used 

https://github.com/facebook/rocksdb/blob/main/INSTALL.md#supported-platforms

https://docs.desmos.network/fullnode/rocksdb-installation/
