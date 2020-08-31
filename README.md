# MAC Address
![](assets/mac-address.png)

# address resolution protocol (ARP)
- ARP helps source machine to obtain target machine eathernet address i.e. mac address
- Generally source machine only has IP address of target machine
- Once source machine gets mac address of target machine then it can send data
![](assets/ip-and-mac.png)
# How to get mac address for given ip address?
- lookup into ARP cache
![](assets/arp-cache.png)
- Check using `arp` cli
![](assets/arp-utilitiy.png)
- Broadcast to all computers in network 
![](assets/broad-cast.png)
# Types of ARP
- Dynamic
  using broadcast approach 
- Static
  Someone manually entered manually
![](assets/arp-static.png)
