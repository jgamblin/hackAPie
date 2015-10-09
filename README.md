#hackAPie
hackAPie is preconfigured Raspberry PI 2 OpenWRT image based off of [this guide](https://devzone.nordicsemi.com/blogs/700/trying-openwrt-chaos-calmer-1505-rc1-on-raspberry-/) and using this [canakit] (http://www.canakit.com/raspberry-pi-starter-kit.html) to provide a safe environment to practice wireless hacking techniques against.  

## How To Install 

**Copy**<br>
Download the hackAPie.img file and follow [this guide](https://www.raspberrypi.org/documentation/installation/installing-images/mac.md).<br>

**Fix the Wifi (Known Bug, I am working in it)**<br>
Plug raspberry pie into your local network. <br> 
scp "wireless config.txt" root@yourip:/etc/config/wireless<br> 

**Reboot**<br>

**Hack**<br>
![Hack](https://d2jhuj1whasmze.cloudfront.net/photos/normal/dArBk.jpg)

## Technical Details:
Username:**root**<br>
Password:**hackapie**<br>

eth0 is configured for DHCP and there is a web interface running on port 80. 

##Wireless Networks:
There are 5 preconfigured wireless networks all running on channel 11.

1: hackAPiehidden<br>
2: hackAPieWEP<br> 
3: hackAPieWPA<br> 
4: hackAPieWPA2<br> 
5: hackAPieWPAMixed<br> 

##Important Notice
I dont know what I am doing. This could be illegal in your country (maybe?).
