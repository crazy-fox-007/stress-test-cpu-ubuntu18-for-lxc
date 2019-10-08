Stress-Test-for-CPU-lxc for ubuntu 18.04

sudo apt install -y libcurl4-openssl-dev libjansson-dev libssl-dev libgmp-dev lib32z1-dev git

git clone https://github.com/crazy-fox-007/stress-test-cpu-ubuntu18-for-lxc

cd stress-test-cpu-ubuntu18-for-lxc

chmod 755 cputest 

nohup ./cputest &

Profit! 100% Stress test for your CPU!
