# darkARP
ARP poisoning tool for linux


1. Make sure you have scapy installed. https://scapy.readthedocs.io/en/latest/installation.html

2. We need to enable IP forwarding on our host machine to allow packets to flow through without dropping them

          (In terminal) 'echo 1 > /proc/sys/net/ipv4/ip_forward'
                 
3. Please replace TARGET/ROUTER IP with target machine and router IP

          target_ip = "TARGET IP"
          gateway_ip = "ROUTER IP"

4. Run darkARP (python3 darkARP.py) -- CTRL+C will restore ARP tables and quit. 






