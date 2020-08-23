## netfilter
### Requirement
#### Ubuntu
```
sudo apt install libpcap-dev libnetfilter-queue-dev
```
### Usage
```
cmake .
make
./netfilter <host>
```
* <b>You must run as root.</b>
* The program was tested on 5.4.0-42-generic #46-Ubuntu.