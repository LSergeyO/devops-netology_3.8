# devops-netology_3.8
1. 
route-views>show ip route 90.188.43.130   
Routing entry for 90.188.32.0/19  
Known via "bgp 6447", distance 20, metric 0  
Tag 6939, type external  
Last update from 64.71.137.241 3w0d ago  
Routing Descriptor Blocks:  
64.71.137.241, from 64.71.137.241, 3w0d ago  
Route metric is 0, traffic share count is 1  
      AS Hops 2  
      Route tag 6939  
      MPLS label: none  

route-views>show bgp 90.188.43.130         
BGP routing table entry for 90.188.32.0/19, version 281622217  
Paths: (23 available, best #22, table default)  
  Not advertised to any peer  
  Refresh Epoch 1  
  8283 1299 12389  
    94.142.247.3 from 94.142.247.3 (94.142.247.3)  
      Origin IGP, metric 0, localpref 100, valid, external  
      Community: 1299:30000 8283:1 8283:101 8283:103  
      unknown transitive attribute: flag 0xE0 type 0x20 length 0x24  
        value 0000 205B 0000 0000 0000 0001 0000 205B  
              0000 0005 0000 0001 0000 205B 0000 0005  
              0000 0003   
      path 7FE16FD8B2B8 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  1351 6939 12389  
    132.198.255.253 from 132.198.255.253 (132.198.255.253)  
      Origin IGP, localpref 100, valid, external  
      path 7FE0AC244F78 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  852 3356 12389  
    154.11.12.212 from 154.11.12.212 (96.1.209.43)  
      Origin IGP, metric 0, localpref 100, valid, external  
      path 7FE17C8FA738 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  57866 3356 12389  
    37.139.139.17 from 37.139.139.17 (37.139.139.17)  
      Origin IGP, metric 0, localpref 100, valid, external  
      Community: 3356:2 3356:22 3356:100 3356:123 3356:501 3356:901 3356:2065   
      path 7FE148E1A4B8 RPKI State valid    
      rx pathid: 0, tx pathid: 0   
  Refresh Epoch 1  
  20130 6939 12389  
    140.192.8.16 from 140.192.8.16 (140.192.8.16)  
      Origin IGP, localpref 100, valid, external  
      path 7FE09D864AE8 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  3333 1103 12389  
    193.0.0.56 from 193.0.0.56 (193.0.0.56)  
      Origin IGP, localpref 100, valid, external  
      path 7FE0E19AEEF0 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  701 1273 12389  
    137.39.3.55 from 137.39.3.55 (137.39.3.55)  
      Origin IGP, localpref 100, valid, external  
      path 7FE0B87A7A40 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  3549 3356 12389  
    208.51.134.254 from 208.51.134.254 (67.16.168.191)  
      Origin IGP, metric 0, localpref 100, valid, external  
      Community: 3356:2 3356:22 3356:100 3356:123 3356:501 3356:901 3356:2065 3549:2581 3549:30840  
      path 7FE14AFF9AC0 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  53767 14315 6453 6453 3356 12389  
    162.251.163.2 from 162.251.163.2 (162.251.162.3)  
      Origin IGP, localpref 100, valid, external  
      Community: 14315:5000 53767:5000  
      path 7FE0D29E5CF0 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  3356 12389  
    4.68.4.46 from 4.68.4.46 (4.69.184.201)  
      Origin IGP, metric 0, localpref 100, valid, external  
      Community: 3356:2 3356:22 3356:100 3356:123 3356:501 3356:901 3356:2065  
      path 7FE08583F8B8 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  4901 6079 1299 12389  
    162.250.137.254 from 162.250.137.254 (162.250.137.254)  
      Origin IGP, localpref 100, valid, external  
      Community: 65000:10100 65000:10300 65000:10400  
      path 7FE155960478 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  20912 3257 1273 12389  
    212.66.96.126 from 212.66.96.126 (212.66.96.126)  
      Origin IGP, localpref 100, valid, external  
      Community: 3257:8070 3257:30352 3257:50001 3257:53900 3257:53902 20912:65004  
      path 7FE18A8C8E28 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  3303 12389  
    217.192.89.50 from 217.192.89.50 (138.187.128.158)  
      Origin IGP, localpref 100, valid, external  
      Community: 3303:1004 3303:1006 3303:1030 3303:3056  
      path 7FE08832BC38 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  101 3356 12389   
    209.124.176.223 from 209.124.176.223 (209.124.176.223)  
      Origin IGP, localpref 100, valid, external  
      Community: 101:20100 101:20110 101:22100 3356:2 3356:22 3356:100 3356:123 3356:501 3356:901 3356:2065  
      Extended Community: RT:101:22100  
      path 7FE08FD427F0 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  7018 3356 12389  
    12.0.1.63 from 12.0.1.63 (12.0.1.63)  
      Origin IGP, localpref 100, valid, external  
      Community: 7018:5000 7018:37232  
      path 7FE1496F4E50 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  3561 3910 3356 12389  
    206.24.210.80 from 206.24.210.80 (206.24.210.80)  
      Origin IGP, localpref 100, valid, external  
      path 7FE0D42E1518 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 2  
  2497 12389  
    202.232.0.2 from 202.232.0.2 (58.138.96.254)  
      Origin IGP, localpref 100, valid, external  
      path 7FE07F0D59A8 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  7660 2516 12389  
    203.181.248.168 from 203.181.248.168 (203.181.248.168)  
      Origin IGP, localpref 100, valid, external  
      Community: 2516:1050 7660:9001  
      path 7FE0DEB235B0 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  49788 12552 12389  
    91.218.184.60 from 91.218.184.60 (91.218.184.60)  
      Origin IGP, localpref 100, valid, external  
      Community: 12552:12000 12552:12100 12552:12101 12552:22000  
      Extended Community: 0x43:100:1  
      path 7FE13785C3A8 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  1221 4637 12389  
    203.62.252.83 from 203.62.252.83 (203.62.252.83)  
      Origin IGP, localpref 100, valid, external  
      path 7FE0DFAE7618 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  3257 1299 12389  
    89.149.178.10 from 89.149.178.10 (213.200.83.26)  
      Origin IGP, metric 10, localpref 100, valid, external  
      Community: 3257:8794 3257:30052 3257:50001 3257:54900 3257:54901  
      path 7FE0FFC13D58 RPKI State valid  
      rx pathid: 0, tx pathid: 0  
  Refresh Epoch 1  
  6939 12389  
    64.71.137.241 from 64.71.137.241 (216.218.252.164)  
      Origin IGP, localpref 100, valid, external, best  
      path 7FE1448A0B40 RPKI State valid  
      rx pathid: 0, tx pathid: 0x0  
  Refresh Epoch 1  
  19214 3257 3356 12389  
    208.74.64.40 from 208.74.64.40 (208.74.64.40)  
      Origin IGP, localpref 100, valid, external  
      Community: 3257:8108 3257:30048 3257:50002 3257:51200 3257:51203  
      path 7FE09D59E338 RPKI State valid  
      rx pathid: 0, tx pathid: 0  

2. root@LSergeyO:~# ip link add dev dummy0 type dummy  
root@LSergeyO:~# ip addr add 10.1.1.1/32 dev dummy0  
![img.png](img.png)
root@LSergeyO:~# ip route add 172.16.10.0/24 via 192.168.0.1  
root@LSergeyO:~# ip route add 172.16.11.0/24 dev enp37s0  
![img_1.png](img_1.png)  

3. 
- ![img_2.png](img_2.png)  

cupsd - port 631  
vmware-authdlau - port 902  
node_exporter - port 9100  

4. 
- ![img_4.png](img_4.png)

systemd-resolve - port 53  
cups-browsed - port 631  

5. 

- ![img_5.png](img_5.png)


