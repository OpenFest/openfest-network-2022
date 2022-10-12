Switch ports
============

Core switch ports + panel
-------------------------

port    | panel  | deviceport  | name
--------|--------|-------------|-----------------
Gi1/0/1 |        |             | DEBUG
Gi1/0/2 |        |             | DEBUG/trunk
Gi1/0/3 |        | onboard eth | vin
Gi1/0/4 |        |             | DEBUG/ipacct
Gi1/0/25 |        | WAN         | ap-cf-srv
Gi1/0/26 | 01.06A | WAN         | ap-cf-f-l
Gi1/0/27 | 01.10A | WAN         | ap-cf-f-r
Gi1/0/29 | 01.20A | WAN         | ap-cf-b
Gi1/0/31 | 01.18A | WAN         | ap-cf-a1
Gi1/0/28| 01.08A | WAN         | ap-cf-a2
Gi1/0/33| D22 | WAN         | ap-cf-sc
Gi1/0/30| 01.16A| WAN         | ap-cf-ws
Gi1/0/17| 01.08B | Gi1/0/8     | reception-sw
Gi1/0/18| unknown| Gi1/0/8     | team-sw
Gi1/0/19| 01.19A | Gi1/0/8     | vocsw-A
Gi1/0/20| 01.16A | Gi1/0/8     | vocsw-B
Gi1/0/21|  | Gi1/0/8     | 
Gi1/0/22| 01.21A| Gi1/0/8     | ws-sw
Gi1/0/24| 01.18B |             | presenter-A 
Gi1/0/25| 01.17A |             | presenter-B
Gi1/0/26| 01.20B |             | presenter-C
Gi1/0/27| 01.09A | eth0        | cambox-B
Gi1/0/28| 01.05A | eth0        | cambox-C
Gi1/0/29| 01.14A | eth0        | overflow
Gi1/0/48|techpark| unknown     | techpark switch
Gi1/0/51|unknown | gi0/49      | f0sw (MM fiber)
Gi1/0/52|unknown | n/a         | ipacct (SM fiber)
Te0/1   |        | enp1s0f0    | vin (MM fiber)

F0 switch ports + panel
-----------------------

port    | panel  | deviceport  | name
--------|--------|-------------|-----------------
Gi0/8   | 01.14A | Gi1/0/24    | nocsw
Gi0/1   | 01.02A | WAN         | ap-ws-ws1  
Gi0/2   | 01.06A | WAN         | ap-ws-ws2
Gi0/9  |unknown | Gi1/0/9    | uplink coresw (MM fiber)

NOC switch WiP
----------

Port    |  Name 
--------|---------
Gi1/0/1 | phone/1       
Gi1/0/2 | phone/2       
Gi1/0/3 | ext/1         
Gi1/0/4 | ext/2         
Gi1/0/5 | of-mgmt/1     
Gi1/0/6 | of-mgmt/2     
Gi1/0/7 | of-wired/1    
Gi1/0/8 | of-wired/2    
Gi1/0/9 | of-wireless/1 
Gi1/0/10| of-wireless/2 
Gi1/0/11| of-video/1    
Gi1/0/12| of-video/2    
Gi1/0/13| of-video/3    
Gi1/0/14| of-video/4    
Gi1/0/15| of-overflow/1 
Gi1/0/16| of-overflow/2 
Gi1/0/17| noc-ap        
Gi1/0/18| noc-int       
Gi1/0/19| noc-int       
Gi1/0/20| noc-int       
Gi1/0/21| noc-int       
Gi1/0/22| AP-FLASH      
Gi1/0/23| uplink(?)
Gi1/0/24| uplink        

