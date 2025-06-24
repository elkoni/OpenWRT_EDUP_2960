OpenWRT ( 24.10.0 ) does not support Edup EP-RT2960S AX1800 China router.  
According to [this](https://openwrt.org/toh/sim/simax1800t), one kan use
sim simax 1800t firmware.  
But the Simax has a different gpios for three-color led and buttons.  
Also ethernet MAC address is in different offset at "factory" partition.  
The patch above fixes this.  
