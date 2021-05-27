# Changing The MAC Address 
## ifconfig  #it list all the network Interface connected to the computer
## ifconfig wlan0 down  #First you have to disable the interface for me wlan0
## ifconfig wlan0 hw ether 00.11.22.33.44.55 #now we Changed the MAC address to Attack
## ifconfig wlan0 up #now interface is enabled you can see the new address
