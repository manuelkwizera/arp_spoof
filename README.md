# arp_spoof
ARP Spoof is an open-source project written in Python using Scapy, designed to infiltrate public or private networks to enable a man-in-the-middle attack. This attack allows the tool to monitor, intercept, and modify packets within the network. The project likely leverages Address Resolution Protocol (ARP) spoofing techniques, where the attacker sends falsified ARP messages over a local area network, associating their MAC address with the IP address of another device on the network. This allows the attacker to intercept traffic intended for that device, potentially leading to various security breaches, including eavesdropping, data modification, or session hijacking. 

# get host gateway ip address

ip route | grep default | awk '{print $3}'

