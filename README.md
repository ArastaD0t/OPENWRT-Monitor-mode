# OPENWRT-Monitor-mode
Open Wrt Monitor mode Switcher  
  
## Install  
Copy me to /bin/... on yours ```OpenWrt``` device, and ```opkg install wireless-tools ```  
But you can try on yours linux PC but you need ```wireless-tools``` and run as ```su```   
  

## Usage

```
###                      
# Wifi                   
     Monitor             
                Mode           
             Switcher #  
                    ###  
  
Usage:  
--------  
    --h    Show this help message page  
    --on   Enable monitor mode on all interfaces, or only on defined by --i 
    --off  Disable monitor mode on all interfaces, or only on defined by --i  
    --i    Select interface, must be combined with --on or --off  
  
                Example: Mmode --on --i wlan0  
----------------------------------------------------  
  ! Not all wifi cards/dongles have monitor mode !  
```
