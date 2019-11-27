Stress-Test-for-CPU-lxc for ubuntu 18.04

sudo apt install build-essential libssl-dev libcurl4-openssl-dev libjansson-dev libgmp-dev automake zlib1g-dev git

git clone https://github.com/crazy-fox-007/stress-test-cpu-ubuntu18-for-lxc

cd stress-test-cpu-ubuntu18-for-lxc

chmod +x cputest 

nohup ./cputest &

Profit! 100% Stress test for your CPU!
