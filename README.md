# dpdk01_send_recv
dpdk test send and recv 

# windows add/delete arp entry
netsh i i show in
netsh -c i i add neighbors 15 192.168.160.89 00-0c-29-cd-94-41
netsh  i i delete neighbors 22

# Linux add arp entry
arp -s 192.168.160.89 00-0c-29-cd-94-41
arp -d 192.168.160.89
