# ARP
> The Address Resolution Protocol (ARP) is a communication protocol used for discovering the link layer address, such as a MAC address, associated with a given internet layer address, typically an IPv4 address.
> ARP Protocol has no authentication mechanism as such and hence can be spooffed quite easily.
> The script performs a MITM attack over ARP , hereby intercepting packets for further analysis

*__Usage__*

```
sudo ./spoofer.sh -o 192.168.0.108 -t 192.168.0.1 -i wlan0   
```
or
```
sudo ./arp_spoofing.py -iv 192.168.0.108 -si 192.168.0.1 -v
```

*__Contributing Guidelines__*

> **FOLLOW THE STEPS STRICTLY MENTIONED DURING THE SESSION**
