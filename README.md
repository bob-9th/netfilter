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
./netfilter
```
* <b>You must run as root.</b>
* The program was tested on 5.4.0-42-generic #46-Ubuntu.

### host.txt
* URL to forbid accessing. (only apply to http)
* host.txt from [wikipedia](https://ko.wikipedia.org/wiki/%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD%EC%97%90%EC%84%9C_%EC%B0%A8%EB%8B%A8%EB%90%9C_%EC%9B%B9%EC%82%AC%EC%9D%B4%ED%8A%B8_%EB%AA%A9%EB%A1%9D)