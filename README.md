# darkARP


## ARP Poison/Spoofer
### Only use this tool on networks/hardware which you personally own, otherwise you are probably committing a crime.



1. Make sure you have scapy installed. https://scapy.readthedocs.io/en/latest/installation.html

2. Enable IP forwarding on host machine so packets don't get dropped

          'echo 1 > /proc/sys/net/ipv4/ip_forward'
                 
3. Replace TARGET/ROUTER IP in the code with the victim machine and gateway/router IP

          target_ip = "TARGET IP"
          gateway_ip = "ROUTER IP"

4. Run darkARP 
          
          python3 darkARP.py
          
          
CTRL+C will restore original ARP tables and quit. 






