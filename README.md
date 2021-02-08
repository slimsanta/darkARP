# darkARP
ARP poisoning tool for linux


Please replace TARGET/ROUTER IP with target machine and router IP
target_ip = "TARGET IP"
gateway_ip = "ROUTER IP"



We need to enable IP forwarding on our host machine to allow packets to flow through without dropping them

In terminal: echo 1 > /proc/sys/net/ipv4/ip_forward

