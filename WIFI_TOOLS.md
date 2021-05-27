# Changing The MAC Address 
### ifconfig  
>it list all the network Interface connected to the computer
### ifconfig wlan0 down  
>First you have to disable the interface for me wlan0
### ifconfig wlan0 hw ether 00.11.22.33.44.55 
>now we Changed the MAC address to Attack
### ifconfig wlan0 up 
>now interface is enabled you can see the new address
---
# Setting up Monitor Mode 
### ifconfig wlan0 down 
### airmon-ng check kill
### iwconfig wlan0 mode moniter
### ifconfig wlan0 up
### iwconfig 
>you can see in the mode is moniter
---
# Alter method to setup Moniter mode
### ifconfig wlan0 down
### airmon-ng check kill
### airmon-ng start wlan0
>you can see the wlan0 in monitor mode as wlan0mon or wlan0
---
# Packet Sniffing
### airodump-ng wlan0mon
>it will display all network around you to quit cltr-c
### 
