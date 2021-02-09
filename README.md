ubuntu 18/20

# driver

sudo apt update

sudo ubuntu-drivers devices

sudo apt install nvidia-driver-450 (select recommended)

reboot

nvidia-smi

# cuda

sudo apt install nvidia-cuda-toolkit

nvcc -V
