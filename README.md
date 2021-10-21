# rogue_dns_server
for dnslog AND dns rebinding attack

install:
require at least python version 3.6, becase of use of f-strings
python module dnslib is needed, install it by:
```
pip3 install dnslib
```

usage:
```
python3 ./server.py

# run background 
nohup python3 -u ./server.py 2>&1 &
```

![image](https://user-images.githubusercontent.com/55265626/138277459-7d63e068-f6e4-4cf7-a490-6fb885d25eaa.png)

