# Simple Flask webapp

Simple application that works on a Raspberry Pi
1. ssh pi@raspberrypi.local
2. git clone the code in this repo
3. docker build . -t <image_name>
4. docker run -p <host_OS_port>:<app_port> <image_name>; <app_port> is 8080
5. get IP of RP: ifconfig -> eth
6. access from laptop browser in same LAN: https://<RP_IP><host_OS_port>
