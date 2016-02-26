# Hotspot-with-Simple-Captive-Portal

The purpose of this system are utilizing Intel NUC5PGYH as a Content Access Point
the plus point are :
  1. Low Power
  2. Intel Wifi Adapter 3165AC  support 802.11ac ( more bandwidth, and more user )
  3. Fast Enough for handling hundreds Concurrent Clients.
  4. Fast enough for embeddeding Web Server for web apps.
  
The infrastructure should be :

---- INTERNET ----|WAN (eth0 ) 
                        NUC5PGYH --- Wifi -----|-- Client ( Notebook )
                                               |-- Clients ( Tablet / Smart Phone)
                                               
Component installed :
1. Ubuntu 15.10 server or later
2. install dnsmasq, hostapd, apache2, php, mysql etc
3. install hotspotd
4. captive portal --> not found yet..
5. create a management system for this infrastructure.

help needed :
1. captive portal
2. simple management web based
