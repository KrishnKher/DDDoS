# DDDoS
## Contents

## Introduction


## Pre-requisite Installations
Follow  the below commands on a terminal to install the required pre-requisites for the working of the code
```
sudo -s
apt remove python2
apt autoremove --purge
pip3 install ryu 
pip3 install eventlet==0.30.2
pip3 install tensorflow
pip3 install cicflowmeter

# To install Tshark follow the below set of commands
wget https://www.wireshark.org/download/src/wireshark-3.0.0.tar.xz -O /tmp/wireshark-3.0.0.tar.xz
tar -xvf /tmp/wireshark-3.0.0.tar.xz
cd /tmp/wireshark-3.0.0
sudo apt update && sudo apt dist-upgrade
sudo apt install cmake libglib2.0-dev libgcrypt20-dev flex yacc bison byacc \
  libpcap-dev qtbase5-dev libssh-dev libsystemd-dev qtmultimedia5-dev \
  libqt5svg5-dev qttools5-dev
cmake .
make
sudo make install

# To Install Hyenae, refer to their github repository
https://github.com/r-richter/hyenae

```
![Untitled presentation](https://user-images.githubusercontent.com/74396985/166516485-1e070697-763e-4b82-bd54-39be19bb8000.png)


